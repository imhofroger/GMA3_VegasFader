# GMA3_VegasFader

All Files and infos you need to create Vegas Fader on GrandMA3..  
Plugin and DMX Curves for Import  
Fixture for Import  
Full Showfile with VegasFader Programmed.. -> i mean, DMX Curves are not part of the Showfile!  

## Create DMX Curves

![DimmerCurves](https://github.com/imhofroger/GMA3_VegasFader/blob/5dc2be283a9e4f42687205e15d822f256913bb64/DimmerCurves.png)

##### step 1
| No  | In | Out | Accel | Decel |
| --- | --- | --- | --- | --- |
| 1 | 0 | 0 | 0 | 0 |
| 2 | 0 | 255 | 0 | 0 |
| 3 | 24 | 255 | 0 | 0 |
| 4 | 24 | 0 | 0 | 0 |
| 5 | 255 | 0 | 0 | 0 | 

##### step 2
| No  | In | Out | Accel | Decel |
| --- | --- | --- | --- | --- |
| 1 | 0 | 0 | 0 | 0 |
| 2 | 25 | 0 | 0 | 0 |
| 3 | 25 | 255 | 0 | 0 |
| 4 | 49 | 255 | 0 | 0 |
| 5 | 49 | 0 | 0 | 0 |
| 6 | 255 | 0 | 0 | 0 |

##### step 3
| No  | In | Out | Accel | Decel |
| --- | --- | --- | --- | --- |
| 1 | 0 | 0 | 0 | 0 |
| 2 | 50 | 0 | 0 | 0 |
| 3 | 50 | 255 | 0 | 0 |
| 4 | 74 | 255 | 0 | 0 |
| 5 | 74 | 0 | 0 | 0 |
| 6 | 255 | 0 | 0 | 0 |

##### step 4
| No  | In | Out | Accel | Decel |
| --- | --- | --- | --- | --- |
| 1 | 0 | 0 | 0 | 0 |
| 2 | 75 | 0 | 0 | 0 |
| 3 | 75 | 255 | 0 | 0 |
| 4 | 99 | 255 | 0 | 0 |
| 5 | 99 | 0 | 0 | 0 |
| 6 | 255 | 0 | 0 | 0 |

##### step 5
| No  | In | Out | Accel | Decel |
| --- | --- | --- | --- | --- |
| 1 | 0 | 0 | 0 | 0 |
| 2 | 100 | 0 | 0 | 0 |
| 3 | 100 | 255 | 0 | 0 |
| 4 | 124 | 255 | 0 | 0 |
| 5 | 124 | 0 | 0 | 0 |
| 5 | 255 | 0 | 0 | 0 |

##### step 6
| No  | In | Out | Accel | Decel |
| --- | --- | --- | --- | --- |
| 1 | 0 | 0 | 0 | 0 |
| 2 | 125 | 0 | 0 | 0 |
| 3 | 125 | 255 | 0 | 0 |
| 4 | 149 | 255 | 0 | 0 |
| 5 | 149 | 0 | 0 | 0 |
| 5 | 255 | 0 | 0 | 0 |

##### step 7
| No  | In | Out | Accel | Decel |
| --- | --- | --- | --- | --- |
| 1 | 0 | 0 | 0 | 0 |
| 2 | 150 | 0 | 0 | 0 |
| 3 | 150 | 255 | 0 | 0 |
| 4 | 174 | 255 | 0 | 0 |
| 5 | 174 | 0 | 0 | 0 |
| 6 | 255 | 0 | 0 | 0 |

##### step 8
| No  | In | Out | Accel | Decel |
| --- | --- | --- | --- | --- |
| 1 | 0 | 0 | 0 | 0 |
| 2 | 175 | 0 | 0 | 0 |
| 3 | 175 | 255 | 0 | 0 |
| 4 | 199 | 255 | 0 | 0 |
| 5 | 199 | 0 | 0 | 0 |
| 6 | 255 | 0 | 0 | 0 |

##### step 9
| No  | In | Out | Accel | Decel |
| --- | --- | --- | --- | --- |
| 1 | 0 | 0 | 0 | 0 |
| 2 | 200 | 0 | 0 | 0 |
| 3 | 200 | 255 | 0 | 0 |
| 4 | 224 | 255 | 0 | 0 |
| 5 | 224 | 0 | 0 | 0 |
| 6 | 255 | 0 | 0 | 0 |

##### step 10
| No  | In | Out | Accel | Decel |
| --- | --- | --- | --- | --- |
| 1 | 0 | 0 | 0 | 0 |
| 2 | 225 | 0 | 0 | 0 |
| 3 | 225 | 255 | 0 | 0 |
| 4 | 255 | 255 | 0 | 0 |
| 5 | 255 | 0 | 0 | 0 |

## Fixture

##### Fixture Attributes

![Fixture Attributes](https://github.com/imhofroger/GMA3_VegasFader/blob/698c51c117b84e54c5ade72910d78def11bdd0fe/FixtureAttributes.png)

##### Fixture Channels

![Fixture Channel](https://github.com/imhofroger/GMA3_VegasFader/blob/698c51c117b84e54c5ade72910d78def11bdd0fe/Fixture1.png)

##### Fixture Relations

![Fixture Relations](https://github.com/imhofroger/GMA3_VegasFader/blob/698c51c117b84e54c5ade72910d78def11bdd0fe/Fixture2.png)

## Plugin
```lua
local function main()

	--- Array with all Commands to change the Appearance Color
	local color = {
		'Set Appearance AppNR Color="1,0,0,1" BackR="255" BackG="0" BackB="0" BackAlpha="255"',
		'Set Appearance AppNR Color="1,0.5,0,1" BackR="255" BackG="127" BackB="0" BackAlpha="255"',
		'Set Appearance AppNR Color="1,1,0,1" BackR="255" BackG="255" BackB="0" BackAlpha="255"',
		'Set Appearance AppNR Color="0,1,0,1" BackR="0" BackG="255" BackB="0" BackAlpha="255"',
		'Set Appearance AppNR Color="0,1,0.5,1" BackR="0" BackG="255" BackB="127" BackAlpha="255"',
		'Set Appearance AppNR Color="0,1,1,1" BackR="0" BackG="255" BackB="255" BackAlpha="255"',
		'Set Appearance AppNR Color="0,0.5,1,1" BackR="0" BackG="127" BackB="255" BackAlpha="255"',
		'Set Appearance AppNR Color="0,0,1,1" BackR="0" BackG="0" BackB="255" BackAlpha="255"',
		'Set Appearance AppNR Color="0.5,0,1,1" BackR="127" BackG="0" BackB="255" BackAlpha="255"',
		'Set Appearance AppNR Color="1,0,1,1" BackR="255" BackG="0" BackB="255" BackAlpha="255"'
	}
	local startApp = 201 --- the first Appearance Nr. to use
	local startMacro = 101
 --- the first Macro Nr. to use
	local startRemotes = 1
 --- First Remote Nr.
	local startSeq = 2
 --- the first Sequence  where the additional Dimmer are Stored

	--- Loops! One Loop each VegasFader, and in this one round a second loop for all macros -> Array with colors!
	local i = 1;
	repeat	
		Cmd("Store App "..startApp.." "..startApp..";Assign App "..startApp.." at Seq "..startSeq) --- Create Appearance and assign it to the sequence 
		for col in ipairs(color) do
			--- Create Macro, insert the Command from Color Array
			Cmd("Store Macro "..startMacro.." \""..startApp.."-"..col.."\";Insert Macro "..startMacro..".1;set Macro "..startMacro..".1 command \'"..color[col]:gsub("AppNR", startApp).."\'")
			--- Change location to the Remote Inputs (13.16.3) insert some Remote and assign the right macro
			Cmd("cd 13.16.3;insert;assign macro "..startMacro.." at "..startRemotes..";set "..startRemotes.." key=\"go+\";cd root")
			startMacro = startMacro + 1
 --- Increse Variable
			startRemotes = startRemotes + 1
 --- Increse Variable
			
		end
		--- Change location to the Remote Inputs (13.16.3) insert some Remote and assign the right sequence
		Cmd("cd 13.16.3;insert;assign seq "..startSeq.." at "..startRemotes..";set "..startRemotes.." fader=\"Master\";cd root")
		startApp = startApp + 1 --- Increse Variable
		startRemotes = startRemotes + 1 --- Increse Variable
		startSeq = startSeq + 1 --- Increse Variable
		i = i + 1
 --- Increse Variable
	until(i > 15)
 --- define how many rounds are done.. one round for one VegasFader!

end

return main
```
