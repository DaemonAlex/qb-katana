This isn't really a script but it is a way to add a katana to your server

1. add the katana to your qb-core/shared/items.lua

-- Katanas
['weapon_katanas'] 				 = {['name'] = 'weapon_katanas', 			 	  	['label'] = 'golden katana', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = nil,			['image'] = 'katana.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A Japanese Masterpiece'},




 add the picture that you downloaded in qb-inventory/html/images





 add this to qb-core/shared/weapons.lua
 
  	-- Katanas
[`weapon_katanas`]					= {['name'] = 'weapon_katanas',				['label'] = 'golden katana',						['ammotype'] = nil,						['damagereason'] = 'sliced'},





 add this to qb-weapons/config.lua

"weapon_katanas",