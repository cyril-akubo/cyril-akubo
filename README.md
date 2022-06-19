- 👋 Hi, I’m @cyril-akubo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
cyril-akubo/cyril-akubo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
3
mkdir htmlapp

cd htmlapp
git clone https://github.com/Azure-Samples/html-docs-hello-world.git
resourceGroup=$(az group list --query "[].{id:name}" -o tsv)
appName=az204app$RANDOM
