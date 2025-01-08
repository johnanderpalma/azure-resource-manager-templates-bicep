# Azure Resource Manager Templates (Bicep)

This repository contains a collection of Azure Resource Manager (ARM) templates written in Bicep. Bicep is a domain-specific language (DSL) for deploying Azure resources declaratively. It simplifies the authoring experience with a cleaner syntax and improved modularity compared to traditional JSON ARM templates.

## Getting Started

To get started with these Bicep templates, follow the steps below:

1. **Install Bicep CLI**: Ensure you have the Bicep CLI installed. You can install it using the following command:
    ```sh
    az bicep install
    ```

2. **Clone the Repository**: Clone this repository to your local machine using:
    ```sh
    git clone https://github.com/your-username/azure-resource-manager-templates-bicep.git
    ```

3. **Navigate to Template Directory**: Change to the directory containing the Bicep template you want to deploy:
    ```sh
    cd azure-resource-manager-templates-bicep/templates/<template-directory>
    ```

4. **Deploy the Template**: Use the Azure CLI to deploy the Bicep template:
    ```sh
    az deployment group create --resource-group <your-resource-group> --template-file main.bicep
    ```

## Repository Structure

The repository is structured as follows:

```
azure-resource-manager-templates-bicep/
│
├── templates/
│   ├── template1/
│   │   ├── main.bicep
│   │   └── ...
│   ├── template2/
│   │   ├── main.bicep
│   │   └── ...
│   └── ...
│
└── README.md
```

## Contributing

We welcome contributions to this repository. If you have a new template or improvements to existing templates, please submit a pull request.

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE. See the [LICENSE](LICENSE) file for details.

## Resources

- [Bicep Documentation](https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/)
- [Azure CLI Documentation](https://docs.microsoft.com/en-us/cli/azure/)
- [ARM Templates Documentation](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/)

