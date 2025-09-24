@startuml
left to right direction

actor Cliente
actor Administrador

usecase "Retirar dinero" as UC1
usecase "Depositar dinero" as UC2
usecase "Consultar saldo" as UC3
usecase "Configurar cajero" as UC4

Cliente --> UC1
Cliente --> UC2
Cliente --> UC3
Administrador --> UC4
@enduml
