@startuml
skinparam class {
    BackgroundColor transparent
    BorderColor Black
    FontColor Black
    ArrowColor Black
}

skinparam class<<abstract>>Fontstyle plain

skinparam classAttributeIconSize 0
skinparam style strictuml

class Tile <<abstract>> {
  + gridPosition
  + type
  + virtual void Initialize()
  + virtual void OnPlayerSwap()
}

@enduml