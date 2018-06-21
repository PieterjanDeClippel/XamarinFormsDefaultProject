To increase the startup time of your Xamarin.Forms app
- Open the .csproj file for your Android app in Notepad
- Add following lines within the <b>debug</b> and <b>release</b> xml tag
```xml
<AotAssemblies>True</AotAssemblies>
<EnableLLVM>false</EnableLLVM>
