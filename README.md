# BIM-Example
Revit Custom Addins

## Synopsis

This revit addin allows you to select an element in a revit model and change it's budget parameter values to a certain set of values based on the cost code selected. By selecting a costcode the revit addin automatically fills in the following parameters: CostCode, Cost Code Desc, Division Code, Division Code Description, Work Package, and Cost Type.

## Motivation

Here at Wesex we are all about using the best tools at hand to deliever the best building-designs process possible. In order to do this we have utilized BIM or Building Information Models to allow us to achieve that goal. At the core of Bim lies the I - which means Information. In order to plug relevant information into the model we have created a unique set of budget type parameters which are stored in a shared paramter file, which is loaded into every project. Once this process is done we can then mine the data to enable us to help make better decisions.

## Resources

- The .NET assembly DLL `WesexRibbon.dll`
- The add-in manifest `WesexRibbon.addin`
- Logo
- Input File

## API Reference

Add references to the Revit API assembly files `RevitAPI.dll` and `RevitAPIUI.dll`, located in your Revit installation directory.

## License

There is no license for this project. It is for viewing purposes only!
