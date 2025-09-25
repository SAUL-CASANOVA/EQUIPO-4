@startuml
left to right direction

actor User #3345ccff
actor Driver #3345ccff

rectangle "Use the FRIMUV APP"{
usecase "Register in the movile app" as UC1 #83d3f6
usecase "Log in" as UC2 #83d3f6
usecase "Request a ride to FMAT" as UC3 #83d3f6
usecase "Accept rides" as UC4 #83d3f6
usecase "Evaluate ride" as UC5 #83d3f6
usecase "Optional payment" as UC6 #83d3f6

User --> UC1
User--> UC2
User --> UC3
User --> UC5
User --> UC6
UC1 <-- Driver
UC2 <-- Driver
UC4 <-- Driver
UC5 <-- Driver

}

@enduml
