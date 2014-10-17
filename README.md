Recognise
=========

[![BuildStatus](https://magnum.travis-ci.com/ianjuma/recognise.svg?token=zqBFWpjtmJLRpRDbTde2&branch=master)](https://magnum.travis-ci.com/ianjuma/recognise)

Facial detection and recognition using OpenCV and libfacerec

This is a basic template for my class project - modules are being written

```ruby
require 'know-this'
puts 'The project is in its infancy!'
```

Why yes, contribute, open an issue or make a pull-request

####Install openCV and header files
```
./setup-debian.sh
make get-deps
make
sudo make install
```

#### get gpu and cpu info - openCL integration
```
lspci | grep VGA
cat /proc/cpuinfo | grep sse3
```

#### Don't forget to run tests
```
make test
```

###Algorithms Used

- Principal based approach - eigenfaces
- PCA algorithm
- fisherfaces (local template matching)


###Problem description

- problems of face-detection
- feature extraction techniques
- problems of facial recognition, pattern-matching


###Classification
- gender classification
- ethnic classification
- emotion classification


###Validation
- classification
- learning (ML)


###Pattern Recognition
- object recognition
- number plate recognition & extraction
- movement and pattern extraction
- info extraction on movements


###Improving accuracy of the recogniser
- Lighting conditions (webcam)
- Training with 'realistic' images - good training sets
- Camera with high fps - hd
- Camera LED lighting 30m (poe cam)


###Known Bugs :bug:
- [x] libpq exception


### TODO
- [x] Add Separate conf file
- [x] openCL support, cmake OPENCL=ON, intel GPU support
- [x] Add cmake build, autotools+automake
- [x] Python CL extension - openMP
- [ ] Integrate SMS (AfricaIT)
- [ ] Email notifications Sendgrid
- [ ] Redis cache + store - zmq
- [ ] Better logs + elasticsearch on logs
- [ ] ML and entity classification
- [ ] Video4linux + video face detection and recognition
- [ ] openCL kernels monitoring
- [ ] poe cameras - high fps
- [ ] management console, logging
- [ ] notifications (RESTfull) - service hooks
- [x] postgres integration
- [ ] some graphs on neo4j - gremlin+cypher
