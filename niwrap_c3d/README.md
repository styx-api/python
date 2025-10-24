# NiWrap wrappers for [Convert3D](http://www.itksnap.org/pmwiki/pmwiki.php?n=Convert3D.Convert3D)

Convert3D (unix name c3d) is a command-line image processing tool that offers complementary features to ITK-SNAP. Originally developed to convert between various 3D image formats, the tool has become more of a Swiss army knife for medical image processing. In addition to many standard filters and resampling commands, c3d offers tools specialized for multilabel images (such as segmentation images output by ITK-SNAP) and multicomponent images (such as RGB images read by SNAP). Through the use of reverse polish notation on the command line, c3d allows many image processing tasks to be combined in small command-line mini-programs. This saves on the need to save intermediate image files, saving disk space and network bandwidth. We use c3d extensively to run studies with thousands of 3D images, and are continually adding commands and features to the tool.

Convert3D is made by http://www.itksnap.org/pmwiki/pmwiki.php?n=Convert3D.Convert3D.

This package contains wrappers only and has no affiliation with the original authors.
