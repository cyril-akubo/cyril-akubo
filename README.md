- š Hi, Iām @cyril-akubo
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
cyril-akubo/cyril-akubo is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
3
mkdir htmlapp

cd htmlapp
git clone https://github.com/Azure-Samples/html-docs-hello-world.git
resourceGroup=$(az group list --query "[].{id:name}" -o tsv)
appName=az204app$RANDOM
