# LuaEx
 A collection of scripts that extend Lua's functionality.

 All code is placed in the public domain except where otherwise noted.


----------


## Modules


**I'M CURRENTLY WORKING ON THIS PAGE (Updating every few hours at most until done)**

### enum

#### Features

#### Reserved Enum Names
All Lua Keywords plus LuaEx keywords (const, enum) 

#### Reserved Enum Item Names
- **__count**
- **__first**
- **__getByOrdinal**
- **__hasType**
- **__last**
- **__name**

#### Enum Properties
- **__count** The total number of items in the enum
- **__name** The name of the enum (as a string)

#### Enum Methods
- **__first** Returns the first ordinal item 
- **__hasType**	Determines whether or not a given enum item belongs to this enum 
- **__getByOrdinal** Returns the item with the given ordinal value
- **__last** Returns the last ordinal item 

#### Enum Metamethods
- **__call** Returns an iterator which returns the ordinal value and item object for each enum item
- **__len** Same as the property, __count
- **__tostring** Return a pretty, formatted string of the enum name

#### Item Properties
- id

Item Methods

Item Metamethods


### base64 Module License
 -- Lua 5.1+ base64 v3.0 (c) 2009 by Alex Kloss <alexthkloss@web.de>
 -- licensed under the terms of the LGPL2