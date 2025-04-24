A list of Brewfile templates to help get different types of teams started with default packages.

## How to Use a Brewfile

### On just your local machine

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/lukehefson/brewfiles.git
   cd brewfiles
   ```

2. **Choose a Brewfile**:
   Browse through the available `Brewfile`s in the repository and select one that suits your needs.

3. **Install Packages**:
   Use the `brew bundle` command to install the packages listed in the selected `Brewfile`:
   ```sh
   brew bundle --file=path/to/Brewfile
   
### Deploying across your fleet with Workbrew

1. Get started with Workbrew and deploy it to your fleet
2. Browse through the available `Brewfile`s in this repository and select one that suits your needs
3. Go to https://console.workbrew.com/workspaces/[your workspace]/brewfiles/new and target the Brewfile to all devices or a device group