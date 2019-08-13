 a whole bunch of generator functions
 the main thing they do is replay recorded data
 or look at a table of data and find record matching an index
 we get the data by recording it from the environment
 
 need to be able to transform data by running against existing functions
 need to be able to compose functions
 serially and in parallel
 
 imagine an "eye" that sees a video of a box rotating
 it needs to be able to predict the next frame
 suppose there is an attention mechanism that allows it to
 inspect a portion of the image at a time
 say it imagines that its attention is moving across the image
 it should be able to predict the next portion of the image
 so it needs a model of the image
 
 suppose it cannot "see" all of the pixels at once
 but it can see a more abstract/compositional representation
 and needs to be able to predict the next frame of that
 
 to understand one frame for moving the virtual eye across it
 and predict the next attention frame, it would need to understand edges
 
 when it looks at the image, it gets a large set of numbers from the virtual rods/cones in
 its virtual eye.  it does not initially know which rods/cones are next to each other
 
