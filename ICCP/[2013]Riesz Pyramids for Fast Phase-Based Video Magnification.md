## Riesz Pyramids for Fast Phase-Based Video Magnification

Neal Wadhwa,	Michael Rubinstein,	Frédo Durand and	William T. Freeman

[website](http://people.csail.mit.edu/nwadhwa/riesz-pyramid/) / [pdf](http://people.csail.mit.edu/nwadhwa/riesz-pyramid/RieszPyr.pdf)

### Abstract
We present a new compact image pyramid representation, the Riesz pyramid, that can be used for real-time phase-based motion magnification. Our new representation is less overcomplete than even the smallest two orientation, octave-bandwidth complex steerable pyramid, and can be implemented using compact, efficient linear filters in the spatial domain. Motion-magnified videos produced with this new representation are of comparable quality to those produced with the complex steerable pyramid. When used with phase-based video magnification, the Riesz pyramid phase-shifts image features along only their dominant orientation rather than every orientation like the complex steerable pyramid.

### Bibtex
```
@article{Wadhwa2014RieszPyramid, 
  author = {Neal Wadhwa and Michael Rubinstein and Fr\'{e}do Durand and William T. Freeman},
  title = {Riesz Pyramids for Fast Phase-Based Video Magnification},
  booktitle = {Computational Photography (ICCP), 2014 IEEE International Conference on},
  year = {2014}, 
  organization = {IEEE} 
}
```

### Pros
- less overcomplete (only computed on dominant orientation)
- implemented in spatial domain
- uses efficient, compact linear filters
- real-time capability

### Cons
- can't handel points with non-single dominant orientation
- does not maintain the power of an input signal (may cause minor artifacts)
- can not handle large motion
