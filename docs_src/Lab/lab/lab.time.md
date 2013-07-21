
![Logo](http://underscorediscovery.com/sven/images/logo.png)

#[haxelab](../index.html)
###[Back to types](types.html)

## Lab Time API

The time class offers a consistent method of scheduling things and measuring time in different ways.

_Schedule a function in the future_

**schedule**	time in seconds, function to call, repeat?
`var schedule = Lab.time.schedule( _time_in_seconds:Float, _on_time:Void->Void, ?repeat:Bool = false ) : haxe.Timer`

You can use the return value to cancel the timer, with `schedule.stop()`;

