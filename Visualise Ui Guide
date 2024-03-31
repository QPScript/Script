--\\Loading The Library
local Visualise = loadstring(game:HttpGet('https://raw.githubusercontent.com/hashionsNew/Visualise/main/ui_library.lua'))()


--\\Creating Visualise (Window)
local main = Visualise.create()

--\\Creating a Tab
local Combat = main.create_tab({
  name = 'Combat'--\\TabName
  })
 
Combat.create_label({--\\Creating a Label (Section)
  name = 'CoolStuff',--\\Section Text
  section = 'left'--\\Section Position (left, middle, right)
   })

local Toggle = Combat.create_toggle({--\\Creating a Checkbox Toggle
  name = 'Killaura',--\\Toggle Name
  flag = 'Killaura',--\\Toggle Flag
  checkbox = false,--\\CheckBox Mode
  section = 'left', --\\Toggle Position (left, middle, right)
  callback = function(state: boolean)--\\Callback
  
end})

local Slider = Combat.create_slider({--\\Creating a Slider
 name = 'Slider',--\\Slider Name
 flag = 'Slider',--\\Slider flag
    maximum = 100,--\\Max Value
    minimum = 1,--\\Min Value
    value = 90,--\\Starting Value
    section = 'left',--\\Slider Position (left, middle, right)
    callback = function(state: number)--\\Slider CallBack

end})
