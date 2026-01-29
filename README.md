# vacs Data Repository

This is the central data repository for [**vacs**](https://github.com/MorpheusXAUT/vacs), the **VATSIM ATC Communication System**. It contains the configuration data for Stations, Positions, and Profiles used by vacs to manage diverse ATC setups across the VATSIM network.

By separating configuration from the core application code, we allow FIRs to manage and update their own data independently and define their controllers' experience using vacs.

## Documentation

Comprehensive documentation on how to understand and contribute to this dataset is available in the **[Dataset Documentation](docs/dataset/README.md)**.

This includes guides for:

- [Stations](docs/dataset/stations.md)
- [Positions](docs/dataset/positions.md)
- [Profiles](docs/dataset/profiles.md)

## Contributing

We welcome contributions from FIR staff and community members! Please refer to the [Dataset Documentation](docs/dataset/README.md) for detailed instructions on the file formats and directory structure.

1.  [Fork the repository](https://github.com/MorpheusXAUT/vacs-data/fork).
2.  Make your changes in your FIR's directory (or create it if it doesn't exist).
3.  Validate your changes using the provided JSON schemas.
4.  [Submit a Pull Request](https://github.com/MorpheusXAUT/vacs-data/compare).

## License

The dataset content of this repository is [licensed](LICENSE) under the **[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)** license.

**This means you are free to:**

- **Share** — copy and redistribute the material in any medium or format.
- **Adapt** — remix, transform, and build upon the material.

**Under the following validation terms:**

- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.
- **NonCommercial** — You may not use the material for commercial purposes.
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
