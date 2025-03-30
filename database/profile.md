# Account
ID - int
Email - varchar(255)
First name - varchar(255)
Last name - varchar(255)
Password - varchar(255)

# TFA
ID - int
Account ID - int
Key - varchar(255)
Is verified - bool
Is activated - bool

# Theme 
Account ID
Theme - theme enum

## Theme enum
Light 1
Light 2
Dark 1
Dark 2

# Accessibility
Font size - int
Contrast - float
Saturation - float

# Details
Currency - enum
Logs - text

# Notifications
Notification for budget payment
SMS notifications 
Email notification

