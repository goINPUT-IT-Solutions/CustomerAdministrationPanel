# CAP Data Types

## Customer
- id: Integer
- customerNumber: String
- userName: String
- passwordHash: String
- emailAdress: String
- customerAddresses: Object
- bankAccounts: Object
- orderProcessingContract: Boolean
- bookedContracts: Object
- billingState: Object

## Account
- id: Integer
- userName: String
- passwordHash: String
- customerNumber: String

## Domain
- id: Integer
- domainName: String
- tempDomainName: String
- Type: Integer
- path: String
- sslState: Array
- phpVersion: String
- isActive: Boolean
- DKIMSign: Boolean
- accountId: Integer
- customerNumber: String

## Email
- id: Integer
- domainName: String
- accountName: String
- mailboxSize: Integer
- accountId: Integer
- customerNumber: String

## EmailRedirect
- id: Integer
- domainName: String
- accountName: String
- target: String
- accountId: Integer
- customerNumber: String

## FTPUser
- id: Integer
- userName: String
- passwordHash: String
- path: String
- domainName: String
- permissions: String
- virusScan: Boolean
- accountId: Integer
- customerNumber: String

## DatabaseUser
- id: Integer
- userName: String
- hostName: String
- accountId: Integer
- customerNumber: String

## Database
- id: Integer
- type: string
- databaseName: String
- databaseUsers: String
- accountId: Integer
- size: Integer // Needs manually checking. Stupid mysql.


