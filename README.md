# FC3.0-Hud
Hud inspired on 5City
(It will be updated soon, i made this version in 1-2 hours)

# Dependecies
- ESX Framework
- esx_status
- pma-voice
- Stress System by utku (https://github.com/utkuali/Stress-System-by-utku)
- ox_lib

# Add this to pma-voice>client>module>radio.lua

function GetRadioChannel()
	return radioChannel
end
exports('GetRadioChannel', GetRadioChannel)

function GetRadioChannelUsersCount()

	local count = 0;
 
	for k,v in pairs(radioData) do
 
		count = count + 1;
  
	end
 
	return count
end

exports('GetRadioCount', GetRadioChannelUsersCount)

# Preview

![image](https://github.com/PiotreeQ/FC3.0-Hud/assets/47689001/4e498c65-0c0a-4f09-98a9-afeb4ba8975e)
