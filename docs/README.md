# Telegram.Bots.Extensions.AspNetCore
> Integrate Telegram.Bots Serializer with ASP.NET Core

### Getting Started

#### Configuring the Serializer with ASP.NET Core
```c#
using Microsoft.Extensions.DependencyInjection;
using Telegram.Bots.Extensions.AspNetCore;

...

IServiceCollection services = ...

services.AddControllers()
        .AddBotSerializer();
```

### License

Telegram.Bots.Extensions.AspNetCore is an extension for Telegram.Bots.
Copyright © 2020  Aman Agnihotri (amanagnihotri@pm.me)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with This program.  If not, see [GNU Licenses](https://www.gnu.org/licenses/).

---
