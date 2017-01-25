## Import et export d'autre formats de fichiers

FreeCAD peut importer et exporter de nombreux fromats de fichiers. Voici une liste des plus importants avec une courte description des fonctions disponible :

| Format | Import | Export | Notes |
| ------ | ------ | ------ | ----- |
| STEP   | Oui    | Oui  | C'est le format le plus fidèle d'import / export disponible puisqu'il supporte la géométrie solide et les NURBS. Utilisez-le autant que possible. |
| IGES   | Oui    | Oui    | An older solid format, also very well supported. Some older applications don't support STEP but have IGES. Un format solide plus ancien, également très bien supporté. Certaines applications plus anciennes ne prennent pas en charge le STEP mais ont IGES. |
| BREP   | Oui    | Oui    | The native format of [OpenCasCade](https://en.wikipedia.org/wiki/Open_Cascade_Technology), FreeCAD's geometry kernel.  |
| DXF    | Oui    | Oui    | An open format maintained by Autodesk. Since the 3D data inside a DXF file is encoded in a proprietary format, FreeCAD can only import/export 2D data to/from this format.|
| DWG    | Oui    | Oui    | A proprietary file format. Requires the installation of the [Teigha File Converter](https://www.opendesign.com/guestfiles) utility. This format suffers from the same proprietary limitations as DXF.|
| OBJ    | Oui    | Oui    | A mesh-based format. Can only contain triangulated meshes. All solid and NURBS-based objects of FreeCAD will be converted to mesh on export. An alternative exporter is provided by the Arch workbench, more suited to the export of architectural models.|
| DAE    | Oui    | Oui    | The main import/export format of Sketchup. Can only contain triangulated meshes. All solid and NURBS-based objects of FreeCAD will be converted to mesh on export. |
| STL    | Oui    | Oui    | A mesh-based format, commonly used for 3D printing. Can only contain triangulated meshes. All solid and NURBS-based objects of FreeCAD will be converted to mesh on export. |
| PLY    | Oui    | Oui    | An older mesh-based format. Can only contain triangulated meshes. All solid and NURBS-based objects of FreeCAD will be converted to mesh on export. |
| IFC    | Oui    | Oui    | [Industry Foundation Classes](https://en.wikipedia.org/wiki/Industry_Foundation_Classes). Requires the installation of [IfcOpenShell-python](http://ifcopenshell.org/python.html). The IFC format and its compatibility with other applications is a complex affair, use with care.|
| SVG    | Oui    | Oui    | An excellent, widespread 2D graphics format |
| VRML   | Oui    | Oui    | A rather old mesh-based web format. |
| GCODE  | Oui    | Oui    | FreeCAD can import and export to/from several flavors of GCode, (aka RS-274) but only a small number of machines are supported at the moment. |
| CSG    | Oui    | Non     | Le format OpenSCAD : [CSG](https://fr.wikipedia.org/wiki/Constructive_solid_geometry) (Géométrie de construction de solidesConstructive Solid Geometry). |

Certains de ces formats ont des options qui peuvent être configurés depuis le menu **Édition -> Préférences -> Import/export**
![Import/export preferences](https://www.freecadweb.org/wiki/images/b/bc/Preference_import_export_DXF_fr.png)

**Plus de lecture**

* Tous les formats supportés par FreeCAD: http://www.freecadweb.org/wiki/index.php?title=Import_Export/fr
* Travailler avec les fichiers DXF dans FreeCAD : http://www.freecadweb.org/wiki/index.php?title=Draft_DXF/fr
* Activer le support du DXF et du DWG : http://www.freecadweb.org/wiki/index.php?title=Dxf_Importer_Install/fr
* Travailler avec les fichiers SVG dans FreeCAD : http://www.freecadweb.org/wiki/index.php?title=Draft_SVG/fr
* Importer et exporter au format IFC: http://www.freecadweb.org/wiki/index.php?title=Arch_IFC/fr
* OpenCasCade : http://www.opencascade.com
* Teigha File Converter : https://www.opendesign.com/guestfiles
* Le format IFC : http://www.buildingsmart-tech.org/ifc/IFC4/final/html/index.htm
* IfcOpenShell : http://ifcopenshell.org/
