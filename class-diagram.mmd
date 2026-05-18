classDiagram
    class User {
        -String id
        -String name
        -String email
        -String password
        -String phone
        -String role
        +authenticate(email, password) boolean
        +display() String
    }
    class Customer {
        -String address
        +display() String
    }
    class Admin {
        -String department
        +authenticate(email, password) boolean
        +display() String
    }
    class Vendor {
        <<abstract>>
        -String id
        -String name
        -String category
        -String phone
        -String location
        -double packagePrice
        -boolean available
        +getPackageDescription() String
        +calculateFinalPrice(discountPercent) double
        +display() String
    }
    class Photographer {
        +getPackageDescription() String
    }
    class Catering {
        +getPackageDescription() String
    }
    class Decoration {
        +getPackageDescription() String
    }
    class MusicBand {
        +getPackageDescription() String
    }
    class WeddingEvent {
        -String id
        -String customerId
        -String date
        -String venue
        -int guestCount
        -String theme
        +display() String
    }
    class Booking {
        -String id
        -String customerId
        -String eventId
        -String vendorId
        -String bookingDate
        -String status
        +isConfirmed() boolean
    }
    class Payment {
        -String id
        -String customerId
        -String bookingId
        -double amount
        -double discountPercent
        -String status
        -String paidDate
        +calculateTotal() double
        +invoiceLine() String
    }
    class Budget {
        -String customerId
        -double plannedAmount
        -List~Payment~ payments
        +calculateTotal() double
        +remainingAmount() double
    }
    class Feedback {
        -String id
        -String customerId
        -String name
        -String email
        -int rating
        -String message
        -String status
        -String submittedDate
        +getDisplayText() String
    }
    class Payable {
        <<interface>>
        +calculateTotal() double
    }

    User <|-- Customer
    User <|-- Admin
    Vendor <|-- Photographer
    Vendor <|-- Catering
    Vendor <|-- Decoration
    Vendor <|-- MusicBand
    Payable <|.. Payment
    Payable <|.. Budget
    Customer "1" o-- "*" WeddingEvent : owns
    Customer "1" o-- "*" Booking : creates
    Customer "1" o-- "*" Payment : pays
    Customer "1" o-- "*" Feedback : submits
    WeddingEvent "1" o-- "*" Booking : scheduled for
    Vendor "1" o-- "*" Booking : assigned
    Booking "1" o-- "*" Payment : billed by
    Budget "1" o-- "*" Payment : tracks
