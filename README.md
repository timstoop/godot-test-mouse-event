# Testing Mouse Events

I would expect that the event "mouse\_entered" would trigger when my mouse
pointer enters the CollisionShape2D object. It does not, however. Am I doing
something wrong or am I misinterpreting the event?

## Solution

Right, found it, I need to set `pickable` to `on` in the KineticBody2D. I was
looking for that parameter in the CollisionShape2D instead.
