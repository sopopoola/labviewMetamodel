1) This package allows you to integrate Hawk [1] and EMFCompare[2] with the LabVIEW NXG[3]. Therefore you need all the three tools.
2) The scripts folder contain the Java files for the integration. 
3) Scripts/LabviewModelResourceFactory.java is the script that generate EMF Resource from LabVIEW NXG. see https://www.eclipse.org/hawk/developers/run-from-source/ to run Hawk
4) Scripts/HawkCompare.java is the EMFCompare componenent. Please see https://www.eclipse.org/emf/compare/ to run EMFCompare
5) Scripts/VersionEOLQueryEngine provides high level query support for smells. The function "saveModelN" can generate all the EMF models that has been indexex in Hawk over the lifecycle of the repositories. The function should also generate the changes btween successive versions
6) The folder queries contain the query scripts for each smells.
7) labview.ecore is the labview metamodel. You will need this when running the extended hawk for LabVIEW NXG

References

[1] Hawk- https://www.eclipse.org/hawk/

[2] EMFCompare- https://www.eclipse.org/emf/compare/

[3] LabVIEW NXG- https://www.ni.com/en-us/shop/labview/labview-nxg.html
