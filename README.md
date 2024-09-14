# Task Cancellation in Blazor

This Blazor project demonstrates how to manage and cancel asynchronous tasks using `CancellationTokenSource`. It includes real-time progress tracking and task cancellation features.

## Features

- **Task Cancellation**: Uses `CancellationTokenSource` to cancel running tasks.
- **Progress Tracking**: Monitors and displays task progress with `IProgress<T>`.
- **Async/Await**: Implements asynchronous programming for non-blocking UI updates.
- **Real-Time UI Updates**: Utilizes `StateHasChanged` to refresh the UI dynamically.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/wajid7511/tasks_cancellation_token.git
    ```

2. **Navigate to the Project Directory**
    ```bash
    cd PregressiveApp
    ```

3. **Run the Project**
    Use your preferred IDE or command line to run the Blazor project:
    ```bash
    dotnet run
    ```

4. **Open in Browser**
    Navigate to `http://localhost:5000` (or the specified port) in your web browser to see the application in action.

## Usage

- Click **Run Tasks** to start asynchronous tasks.
- Monitor the progress of each task through the progress bars.
- Click on **Corresponding** button to cancel the corresponding task.

## Code Overview

- **`Pages/Index.razor`**: Contains the Blazor page with UI elements for task control and progress display.
- **`@code` Block**: Manages task execution, cancellation, and UI updates.

## Contributing

Feel free to submit issues, feature requests, or pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [Wajid Nazar Muhammad](mailto:email2wajidkhan@gmail.com).

