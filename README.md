    ███╗   ███╗███████╗████████╗███████╗██╗  ██╗    ██╗      █████╗ ██████╗ ██████╗
    ████╗ ████║██╔════╝╚══██╔══╝██╔════╝╚██╗██╔╝    ██║     ██╔══██╗██╔══██╗██╔════╝
    ██╔████╔██║█████╗     ██║   █████╗   ╚███╔╝     ██║     ███████║██████╦╝╚█████╗
    ██║╚██╔╝██║██╔══╝     ██║   ██╔══╝   ██╔██╗     ██║     ██╔══██║██╔══██╗ ╚═══██╗
    ██║ ╚═╝ ██║███████╗   ██║   ███████╗██╔╝╚██╗    ███████╗██║  ██║██████╦ ██████╔╝
    ╚═╝     ╚═╝╚══════╝   ╚═╝   ╚══════╝╚═╝  ╚═╝    ╚══════╝╚═╝  ╚═╝╚═════╝ ╚═════╝
# Swarm Runner

## Overview

Welcome to Swarm Runner, a tool designed to facilitate joining the Metex private swarm by providing GPU support to the network. This application is publicly available for everyone interested in contributing their GPU resources to the Metex swarm.

## Getting Started

### Prerequisites

Before using Swarm Runner, ensure that you have the following prerequisites installed:

- NVIDIA GPU with CUDA support
- Windows operating system

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/metex/swarm-runner.git
   ```

2. Navigate to the project directory:

   ```bash
   cd swarm-runner
   ```

3. Run the executable file `SwarmRunner.exe`:

   ```bash
   ./SwarmRunner.exe
   ```

## Usage

1. Launch the application and follow the on-screen instructions.

2. Enter your Metex swarm credentials when prompted.

3. The application will automatically utilize your GPU resources to contribute to the Metex private swarm.

## Contributing

We welcome contributions from the community. If you'd like to contribute to the development of Swarm Runner, please follow these guidelines:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add your commit message here"
   ```

4. Push your branch to your fork:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a pull request on the main repository.


## Human-Error
In case if you get a "Unrecogonised Argument" error

    ```run_server.py: error: unrecognized arguments: black sheep have you any wool
       Traceback (most recent call last):
       File "C:\Users\ADNANB~1\AppData\Local\Temp\Client_runner.py", line 495, in <module>
       run_petals_server(server_options[server_option])
       File "C:\Users\ADNANB~1\AppData\Local\Temp\Client_runner.py", line 347, in run_petals_server
       run_command(command)
       File "C:\Users\ADNANB~1\AppData\Local\Temp\Client_runner.py", line 13, in run_command
       subprocess.run(command, shell=True, check=True)
       File "C:\Users\Adnan Baqi\AppData\Local\Programs\Python\Python310\lib\subprocess.py", line 524, in run
       raise CalledProcessError(retcode, process.args,
       subprocess.CalledProcessError: Command 'wsl python -m petals.cli.run_server petals-team/StableBeluga2 --public_name baba black sheep have you any wool --initial_peers /ip4/45.79.153.218/tcp/31337/p2p/QmXfANcrDYnt5LTXKwtBP5nsTMLQdgxJHbK3L1hZdFN8km --public_ip 
       xxx.xxx.xxx --port xxxxx' returned non-zero exit status 2.```


1. Try not to add spaces between your name

   ```bash
   --public_name baba black sheep have you any wool
   ```

2. Replace the spaces in the `--public_name` argument with underscores and add your name. For example, change:

   ```bash
   --public_name baba_black_sheep_have_you_any_wool
   ```

This way, you've added your name in the correct format.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For any issues, bugs, or questions, please open an [issue](https://github.com/metex/swarm-runner/issues).

## Disclaimer

Swarm Runner is provided as-is, without any guarantees or warranties. Use it at your own risk.

Happy Swarming!
