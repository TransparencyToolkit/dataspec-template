# dataspec-template

A template for making LookingGlass dataspec packages

**Using this package**

1. Install [LookingGlass](https://github.com/TransparencyToolkit/LookingGlass)
2. Go into the `app/dataspec/` directory 
3. Clone this spec package `git clone https://github.com/TransparencyToolkit/dataspec-template.git`
4. Add this dataspec package to your `instances/config.json` file
5. Configure the JSON files in this folder as per [our documentation](https://github.com/TransparencyToolkit/LookingGlass/DATASET-SPECIFICATION.md)

```
{
    "Dataset Config": ["app/dataspec/dataspec-template/"],
    "Page Title": "Your LookingGlass App",
    ...
```
