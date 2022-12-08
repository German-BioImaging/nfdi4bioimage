### OME Data Model
The model includes image parameters, such as XYZ dimensions and pixels type, as well as extensive metadata on, for example, image acquisition, annotation, and regions of interest (ROIs). This common specification is essential for the exchange of image data between different software packages.

- **Overview:** https://docs.openmicroscopy.org/ome-model/6.0.1/
- **Schema:** https://www.openmicroscopy.org/Schemas/Documentation/Generated/OME-2016-06/ome.html
- **API/Interfaces:** XSD-based model
- **Formats:** XML (embedded in TIFF)
- **Tools/Libs:** [Bio-Formats](https://github.com/ome/bioformats), [omero-rdf](https://github.com/German-BioImaging/omero-rdf), [MDEmic](/https://omero-guides.readthedocs.io/en/latest/mde/docs/index.html)

### OME-NGFF metadata
- **Overview:** https://ngff.openmicroscopy.org/latest/#metadata
- **Forum:** https://forum.image.sc/tag/ome-ngff
- **Formats:** JSON-LD embedded in [Zarr](https://zarr.dev/)
- **Github:** https://github.com/ome/ngff
- **Issues:** https://github.com/ome/ngff/issues/15, 

### 4DN-BINA-OME (NBO) Microscopy Metadata
Extension of the OME Data Model, intended to be based on the JSON-LD representation
- **Overview:** https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs
- **API/Interfaces:** XSD-based model
- **Formats:** JSON
- **Tools/Libs:** [Micro-Meta-App](https://wu-bimac.github.io/MicroMetaApp.github.io/)
- **Github:** https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/tree/master/Model/in%20progress/v02-10
