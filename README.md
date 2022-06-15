# Repro Steps
- `cd ./my-appshell` and run `npm i` and then `npm run build`
- `cd ../my-pilet` and run `dotnet build`
- `cd ../piral~/my-pilet` and run `npm start`

# Problem
When you click `View Item` in the top right you will be redirected to `/item/single/123456789`.
Here you can see that the ID is nor read from the url.
The relevant Code can be found in `my-pilet\Pages\Item.razor`.