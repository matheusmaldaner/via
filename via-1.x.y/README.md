# VGG Image Annotator Version 1

VGG Image Annotator version 1 is an early version of VIA which is still useful
for basic image annotation tasks. VIA runs in a web browser and
does not require any installation or setup. The complete VIA software fits in a 
single self-contained HTML page of size less than 300 Kilobyte that runs as an 
offline application in most modern web browsers.

VIA is an [open source](https://gitlab.com/vgg/via) project based solely on 
HTML, Javascript and CSS (no dependency on external libraries). VIA is 
developed at the [Visual Geometry Group](http://www.robots.ox.ac.uk/~vgg/) (VGG) 
and released under the BSD-2 clause [license](https://gitlab.com/vgg/via/blob/master/LICENSE)
which allows it to be useful for both academic projects and commercial applications.

## Screenshots
![Screenshot showing basic image annotation](doc/screenshots/big_ben_annotation.jpg)

## Download
Detailed instructions for download of VIA are available at http://www.robots.ox.ac.uk/~vgg/software/via/

## Demo
We have created self contained demo to illustrate the usage of VIA3. These demo
have been preloaded with some sample audio and video files. Furthermore, we have 
also added some sample manual annotations to these demo. These demo applications 
are very useful to get familiar with the commonly used features of VIA3.
  * [Basic Image Annotation Demo](http://www.robots.ox.ac.uk/~vgg/software/via/via-1.0.6_demo.html)

## Open Source Ecosystem
The development of VIA software began in August 2016 and the first public
release of version 1 was made in April 2017. Many new advanced features
for image annotation were introduced in version 2 which was released in June 2018. 
Recently released version 3 of VIA software supports annotation of audio and video. 
As of May 2019, the VIA software has been used more than 600,000 times (+150,000 unique pageviews).

We have nurtured a large and thriving open source community which not
only provides feedback but also contributes code to add new features
and improve existing features in the VIA software. The open source
ecosystem of VIA thrives around its [source code repository](https://gitlab.com/vgg/via)
hosted by the Gitlab platform. Most of our users report issues and
request new features for future releases using the [issue portal](https://gitlab.com/vgg/via/issues). 
Many of our users not only submit bug reports but also suggest a potential
fix for these software issues. Some of our users also contribute code
to add new features to the VIA software using the [merge request portal](https://gitlab.com/vgg/via/merge_requests). 

We welcome all forms of contributions (code update, documentation, bug reports, etc) from users. 
Such contributions must must adhere to the existing [license](https://gitlab.com/vgg/via/blob/master/LICENSE) of 
the VIA project.

## Developer Resources
For development, [via.js](https://gitlab.com/vgg/via/blob/develop/via.js) 
contains the Javascript source code and 
[index.html](https://gitlab.com/vgg/via/blob/develop/index.html) contains the 
HTML and CSS. The shell script [pack_via.sh](https://gitlab.com/vgg/via/blob/develop/pack_via.sh) 
packs the VIA application into a single and standalone application file 
[via.html](https://gitlab.com/vgg/via/blob/develop/via.html) containing the 
Javascript, HTML and CSS.

 * Source code
   * [VGG Image Annotator @ develop branch](https://gitlab.com/vgg/via/blob/master/via-1.x.y)
 * [Source code documentation](https://gitlab.com/vgg/via/blob/master/via-1.x.y/CodeDoc.md)
 * [Contributing Guidelines](https://gitlab.com/vgg/via/blob/master/via-1.x.y/CONTRIBUTING.md)
 * Unit Tests
   * [tests/via_test_fileio.js](via-1.x.y/tests/via_test_fileio.js) : tests for import/export of annotations
   * [tests/via_test_region.js](via-1.x.y/tests/via_test_region.js) : tests for region create, move, delete operations

The [Quality Assessment](https://gitlab.com/vgg/via/blob/master/via-1.x.y/QualityAssessment.md) 
page describes the guidelines to ensure the quality of VIA application, source 
code and its documentation.


## Citation
If you use this software, please cite it as follows:

<cite>Abhishek Dutta and Andrew Zisserman. 2019. <a href="docs/dutta2019vgg_arxiv.pdf">The VIA Annotation Software for Images, Audio and Video</a>. In Proceedings of the 27th ACM International Conference on Multimedia (MM ’19), October 21–25, 2019, Nice, France. ACM, New York, NY, USA, 4 pages. https://doi.org/10.1145/3343031.3350535</cite>.

```
@inproceedings{dutta2019vgg,
  author = {Dutta, Abhishek and Zisserman, Andrew},
  title = {The {VIA} Annotation Software for Images, Audio and Video},
  booktitle = {Proceedings of the 27th ACM International Conference on Multimedia},
  series = {MM '19},
  year = {2019},
  isbn = {978-1-4503-6889-6/19/10},
  location = {Nice, France},
  numpages = {4},
  url = {https://doi.org/10.1145/3343031.3350535},
  doi = {10.1145/3343031.3350535},
  publisher = {ACM},
  address = {New York, NY, USA},
} 

@misc{dutta2016via,
  author = "Dutta, A. and Gupta, A. and Zissermann, A.",
  title = "{VGG} Image Annotator ({VIA})",
  year = "2016",
  howpublished = "http://www.robots.ox.ac.uk/~vgg/software/via/",
  note = "Version: X.Y.Z, Accessed: INSERT_DATE_HERE" 
}
```

## Contact
Contact [Abhishek Dutta](adutta_remove_me_@robots.ox.ac.uk) for any queries or feedback related to this application.

## Acknowledgements
This work is supported by EPSRC programme grant Seebibyte: Visual Search for the Era of Big Data ( [EP/M013774/1](http://www.seebibyte.org/index.html) )

