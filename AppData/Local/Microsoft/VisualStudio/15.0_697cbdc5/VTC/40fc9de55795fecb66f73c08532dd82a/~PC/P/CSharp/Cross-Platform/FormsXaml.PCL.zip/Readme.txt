This PCL template just adds App.xaml and MainPage.xaml to the 
PCL project. As such, all the App "heads" are actually exactly
the same as for the Blank PCL app. 

Therefore, the .csproj defines Include item metadata for the 
FormsXaml.PCL.vstemplate item, as well as Exclude to remove 
the .vstemplate and main PCL project from the Forms.PCL template.