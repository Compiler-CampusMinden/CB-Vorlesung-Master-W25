# Interpreter

Ein Interpreter erzeugt keinen Code, sondern führt Source-Code
(interaktiv) aus. Die einfachste Möglichkeit ist der Einsatz von
attributierten Grammatiken, wo der Code bereits beim Parsen ausgeführt
wird (“syntaxgesteuerte Interpretation”). Mehr Möglichkeiten hat man
dagegen bei der Traversierung des AST, beispielsweise mit dem
Visitor-Pattern. Auch die Abarbeitung von Bytecode in einer Virtuellen
Maschine (VM) zählt zur Interpretation.

(Register- und Stack-basierte Interpreter betrachten wir im Rahmen der
Veranstaltung aktuell nicht.)

------------------------------------------------------------------------

<img src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" width="10%">

Unless otherwise noted, this work is licensed under CC BY-SA 4.0.

<blockquote><p><sup><sub><strong>Last modified:</strong> 8e348b3 (Remove Hugo: tooling: do not generate beamer slides for readme's and homework, 2025-07-29)<br></sub></sup></p></blockquote>
