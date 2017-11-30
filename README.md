# "Huge Dirty Cow" POC

A POC for the Huge Dirty Cow vulnerability (CVE-2017-1000405). Full details can be found [here](https://medium.com/bindecy/huge-dirty-cow-cve-2017-1000405-110eca132de0).

Before running, make sure to set transparent huge pages to "always":
```
echo always | sudo tee /sys/kernel/mm/transparent_hugepage/enabled
```



