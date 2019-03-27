# FFMPEG NuGet Spec


### Building
1. First, download the required ffmpeg binaries and place them into the appropriate sub-folder (yout will need to create these folders if they don't exist).
    - For 32-bit, use `x86/ffmpeg`
    - For 64-bit, use  `x64/ffmpeg`
2. Update the nuspec files. The relevant fields are :
    - `version` - use `<ffmpeg_version>.1`
    - `releaseNotes` - update as required
3. Run the nuget package command
    - `nuget pack <nuspec_file>`
4. Upload the nupkg file to NuGet.
