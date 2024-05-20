# PayloadDumperWorkflow

Workflow for payload dumper by 5ec1cff

## How to use it?

 1. Fork this repository
 2. In your fork, go to the “Actions” page
 3. Select “Payload Dumper Workflow” on the side
 4. Click “Run workflow”.
 5. Specify the URL to download the OTA archive (must have .zip at the end)
 6. Specify the sections you want to dump
 7. Wait for execution...
 8. After the run (green check mark) you will be able to find the archive in artifacts, it will contain the sections you have selected.
 9. Profit!

## Credits

- [nnsee](https://github.com/nnsee/payload-dumper): original payload-dumper on python
- [5ec1cff](https://github.com/5ec1cff): modified payload-dumper (downloading from the server, etc.)