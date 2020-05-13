Install Deno
Powershell: iwr https://deno.land/x/install/install.ps1 -useb | iex
Bash(mac/*nix): curl -fsSL https://deno.land/x/install/install.sh | sh

to run use command: deno run --allow-net ./src/server.ts

Create an api
- receive http requests
- serve http responses