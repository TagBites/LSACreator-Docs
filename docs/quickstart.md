# Quick start

1. **Create a new project**.
2. **Add your assemblies (.exe or .dll files).**  
*LSACreator will scan your assemblies (.exe/.dll) for resources which contains at least one string and present them in tree view.*
3. **Add a new languages for specific resource, assembly or whole project.**
4. **Translate your resources.**
5. **Build the project.**  
*In bin directory of language project LSACreator will create a folder for every language. Each folder will contain assemblies with translated resources only.*
6. **Copy language folders to your application directory.**  
*Now your application supports new languages thanks to satellite assemblies.*

## Working with WinForms

If you are using WinForms, you have to set property **“Localizable”** to **“true”** in dialog designer (for all forms). This way Visual Sudio will create a resource for your dialog or control.

## Working with source protector/obfuscator

If you are using some kind of source protector/obfuscator, then make sure it is not encrypting your resources. If you can see your resource and its strings in ILSpy or Reflector it means that LSACreator can see it too.
