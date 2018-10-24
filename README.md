# esx_fuelerjob

## Requirements

* Auto mode
   - [esx_service](https://github.com/FXServer-ESX/fxserver-esx_service)

* Player management
   - [esx_society](https://github.com/ESX-Org/esx_society)
   - [esx_billin](https://github.com/FXServer-ESX/fxserver-esx_billing)

## Installation
- Import `esx_fuelerjob.sql` in your database
- If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`
- Add this in your `server.cfg`:

```
start esx_fuelerjob
```

