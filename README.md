# mvc-application

The LH Pet Internal Control System is a web application designed to manage and display client and supplier information for a pet services company. The system allows users to view lists of clients and suppliers, including their key details such as identification numbers, contact information, and additional attributes specific to clients or suppliers.

## Features

- **Client Management**: Display client details including ID, name, CPF, email, and pet name.
- **Supplier Management**: Display supplier details including ID, name, CNPJ, and email.
- **Dynamic Data Rendering**: Client and supplier data is dynamically rendered using Razor syntax.

## Installation

1. **Clone the repository**:
   ```bash
   git clone git@github.com:MateusjsSilva/mvc-application.git
   cd mvc-application/Application.MVC
   ```

2. **Build the project**:
    ```bash
    dotnet build
    ```

3. **Run the application**:
    ```bash
    dotnet run
    ```

- The application will start and be available at `http://localhost:[PORT]`, where `[PORT]` is the port automatically assigned by .NET or specified by the user.

## Contribution

Feel free to open issues or submit pull requests. All contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.