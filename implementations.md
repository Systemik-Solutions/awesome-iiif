# Implementations

A lightly edited list of sites that have implemented at least one of the IIIF standards.

**Guidelines:** New additions should be placed at the end of the list. The label of the link should be the name of the site. The description should include the publisher (usually an institution), and the publisher may be a link to contact information. The description can also include information on which of the APIs have been implemented.

- [Historical State Search](http://historicalstate.lib.ncsu.edu/search) displays images via a IIIF image server.
- [FromThePage](http://www.fromthepage.com) ingests IIIF manifests and displays images for transcription using OpenSeaDragon.
- [SAT Taishōzō Image DB](http://dzkimgs.l.u-tokyo.ac.jp/SATi/images.php?alang=en) by the SAT Daizōkyō Text Database Committee in the DH initiative, the University of Tokyo adopts the IIIF Image and Presentation APIs including over 4,000 annotations displayed on Mirador.
- [e-codices](http://www.e-codices.unifr.ch) provides access to 1,700+ Swiss medieval manuscripts (ca. 500,000 high-res images) via IIIF. The IIIF manifest link for individual manuscripts can be found on the overview page of each manuscript (see [example](http://www.e-codices.unifr.ch/en/searchresult/list/one/csg/0857)). IIIF collection of collections with links to all manifests here: <http://www.e-codices.unifr.ch/metadata/iiif/collection.json>.
- [Gallica](http://gallica.bnf.fr/) is the digital library of the Bibliothèque nationale de France (BnF), providing access to millions of documents (newspapers and journals, maps, printed books, manuscripts, scores etc.). It implements the Image API and the Presentation API. [More technical details](http://doc.biblissima-condorcet.fr/entrepots-iiif-biblissima) about the IIIF endpoints (images and manifests).
- [Biblissima reconstituted manuscript demo](http://demos.biblissima-condorcet.fr/chateauroux/osd-demo/) presents a manuscript where illuminations had been cut out and then allows for reconstituting the manuscript by placing those images back into place.
- [NCSU Libraries Rare and Unique Digital Collections](https://d.lib.ncsu.edu/collections/) implements the Image, Presentation, and Content Search APIs.
- [DigiVatLib](http://digi.vatlib.it/) provides access to digitized collections from the Vatican.
- [Georeferencer](http://www.georeferencer.com/) can take maps accessible via IIIF and referenced to modern maps.
- [hocrviewer](https://github.com/jbaiter/hocrviewer-mirador) can display and search OCRed documents in the [hOCR format](http://kba.github.io/hocr-spec/1.2/) with Mirador. Contains a simple implementation of the Content Search API with SQLite.
- [The SCTA Reading Room](http://scta.lombardpress.org/) - A site for reading, viewing, and studying the scholastic tradition.
- [Yale Center for British Art](http://britishart.yale.edu/) provides at least 80,000 images via the IIIF Image and Presentation APIs, using the Cantaloupe IIIF Server. See example [item record](http://collections.britishart.yale.edu/vufind/Record/1669236), [top-level collection manifest](http://manifests.britishart.yale.edu/collection/top), and [example IIIF Presentation API manifest](http://manifests.britishart.yale.edu/manifest/5005).
- [Harvard Art Museums](http://www.harvardartmuseums.org/) serves over 200,000 images via the IIIF Image and Presentation APIs, using Mirador. See [example item](http://www.harvardartmuseums.org/tour/drawing-the-invention-of-a-modern-medium/slide/8568) and [example manifest](http://iiif.harvardartmuseums.org/manifests/object/299843).
- [Carnegie Museum of Art](http://cmoa.org/about/) utilizes the IIIF Image API level 0 for static files, with links to manifests provided on object pages, using an OpenSeadragon client and Amazon S3 to store images. See example [collection manifest](https://cmoa-records-images.s3.amazonaws.com/collection/top.json) and [object manifest](http://cmoa-records-images.s3.amazonaws.com/fv001_001_003_001_B014_F05_002/manifest.json), as well as [implementation code documentation](https://github.com/cmoa/iiif_s3).
- [The Frick Collection](http://digitalcollections.frick.org/digico/#/) allows users to compare multiple images in Mirador.
- [DigiPress - The newspaper portal of the Bayerische Staatsbibliothek (Bavarian State Library)](https://digipress.digitale-sammlungen.de/) now supports IIIF - see a [sample issue](https://digipress.digitale-sammlungen.de/view/bsb00012484_00382_u001/1), [sample collection](https://api.digitale-sammlungen.de/iiif/presentation/bsb00012484/view.html), and [collection manifest](https://api.digitale-sammlungen.de/iiif/presentation/v2/bsb00012484/manifest).
- [Beyond Words: Illuminating Manuscripts in Boston Collections](http://beyondwords2016.org/) multi-institutional collaboration using annotated IIIF manifests and Mirador (see [example](http://beyondwords2016.org/objects/leaves-from-an-antiphonal-and-a-gradual)).
- [The Wolsey Manuscripts](http://www.wolseymanuscripts.ac.uk/manuscripts) using reunification functionality and Mirador.
- [Cuban Digital Collections] (http://iiif.sld.cu/) A collaboration project between cuban libraries to publish digital collections of cultural heritage works using IIIF standards. 
- [DIGITAL EAST ASIA COLLECTIONS of the Bavarian State Library](https://ostasien.digitale-sammlungen.de/?locale=en) provides digitized versions of Chinese, Japanese and Korean printings and manuscripts (dating back to the 7th – 19th century) which are held by the Bavarian State Library (BSB)
- [Digital Collections iiif of the Bavarian State Library](https://app.digitale-sammlungen.de/bookshelf/?language=en) provides access to the digitized objects of the Bavarian State Library utilizing the IIIF-APIs and Mirador
- [University of Illinois at Urbana-Champaign Library](https://digital.library.illinois.edu/items?fq%5B%5D=primary_media_category%3A0) uses IIIF and UniversalViewer for presenting their image collections on their Digital Collections website. IIIF manifest.json and info.json are provided under the button "View" on the viewer's page (top right).
