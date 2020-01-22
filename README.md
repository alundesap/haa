haa
===

SAP HANA Academy - SAP HANA Service - Analytics Adapter

```
git checkout ext ; git pull ; mbt build -p=cf -t=target --mtar=haa-ext.mtar ; cf deploy target/haa-ext.mtar -f

git checkout dedext ; git pull ; mbt build -p=cf -t=target --mtar=haa-dedext.mtar ; cf deploy target/haa-dedext.mtar -f

mbt build -p=cf -t=target --mtar=haa-dedext.mtar ; cf deploy target/haa-dedext.mtar -f

```
