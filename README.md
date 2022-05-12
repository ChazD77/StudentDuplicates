UPDATE Customers

SET RecordCode = 'Active', AttendanceStatus = 'Enrolled'

WHERE AttendanceStatus <> 'Enrolled'
