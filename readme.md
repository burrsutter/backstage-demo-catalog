# Demo Catalog Entries

This repository is to maintain Backstage Catalog entities for demo purposes.   

Use the URL to the catalog_main.yaml file 

https://github.com/burrsutter/backstage-demo-catalog/blob/main/catalog_main.yaml

Register Component on the Create screen

Note: You can re-import the catalog_main.yaml in which case you will be presented with a "Refresh" button

![0](/images/register-0.png)

![1](/images/register-1.png)

![2](/images/register-2.png)

![3](/images/register-3.png)

![4](/images/register-4.png)

![5](/images/register-5.png)

# Tips

https://backstage.io/docs/features/software-catalog/descriptor-format/

# Maintenance of catalog-main.yaml

rm catalog_main.yaml
cat sso_system.yaml >> catalog_main.yaml
echo "\n" >> catalog_main.yaml
cat customerweb_system.yaml >> catalog_main.yaml
echo "\n" >> catalog_main.yaml
cat training_system.yaml >> catalog_main.yaml
echo "\n" >> catalog_main.yaml
cat marketing_system.yaml >> catalog_main.yaml