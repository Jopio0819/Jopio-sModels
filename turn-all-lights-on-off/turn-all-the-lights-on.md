# Turn all the lights on

In order to set all the lights on, your script should look a bit like this:

```lua
function On()
local model = game.Workspace["Jopio's Light System"]
local api = model.Zones.Trigger

	api:Fire("On","0")
end

-- Your logic here, to fire the function.
```

It is very easy, and can be done by anyone!

{% hint style="danger" %}
Dont forget to add the "" for the zone. Else the system will crash.
{% endhint %}
