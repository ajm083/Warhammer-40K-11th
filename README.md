##Dataset Test

This is a test for learning to make datasets - might not be up to date or even finished at all

## Creating your own dataset

1. Fork this repository, then clone your fork locally.
2. Start with the [minimal worked example](#minimal-worked-example) below, or use the JSON files in the [Fracture example folder](WarOrgan.Data.BuildDataset/Assets/Fracture) for more detailed examples.
3. Add your own asset folder, including a `README.md`, and update `defaultDatasetId`, `defaultVersion` and `assetsFolder` in your copy of `Program.cs`.
4. Run the builder, resolve any validation errors, and import the generated ZIP into WarOrgan using the steps above.

For compatibility with the existing WarOrgan app, adapt your data and build process to the supplied model. You are free to modify the model in your own project under the MIT licence, but those changes may require corresponding changes to the app.

