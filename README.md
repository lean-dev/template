# Projekt: Lean Angular Template

> Projektvorlage für meine Angular-Anwendungen

## Installation

- GitHub Template
- Via giget oder degit

      # <project-name> ist der neue Ordnername
      npx giget@latest gh:lean-ng/template <project-name>

      # oder alternative
      npx degit lean-ng/template <project-name>

## Opinionated Decisions for angular.json

- Tests: alles bzgl. des Unit Testing wird aus dem Projekt entfernt und auch
  keine Tests mehr automatisch mit erzeugt für neue Angular-Artefakte. Die
  Entscheidung über konkrete Werkzeuge (Task Runner, Framework, Libraries) wird
  nach hinten geschoben - aber natürlich nicht aufgehoben.
