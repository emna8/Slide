This SAP template just adds App.xaml and MainPage.xaml to the 
Shared project. As such, all the App "heads" are actually exactly
the same as for the Blank SAP app. 

Therefore, the .csproj defines Include item metadata for the 
FormsXaml.Shared.vstemplate item, as well as Exclude to remove 
the .vstemplate and main SAP project from the Forms.Shared template.