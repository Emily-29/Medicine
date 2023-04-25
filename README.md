"# Medicine" 

breast:

  _unprocessed raw image: (x4/x2:384x384)
  
  _LR: Downsampled input image (x4/x2:96x96)
  
  _org: Original image (same size as _HR, used to calculate loss) (x4:384x384, x2:192x192)
  
  _HR: Output image of the model (_LR image is input) (x4:384x384, x2:192x192)
  
  _SR: Output image of the model (_unprocessed raw image is input) (x4:1536x1536, x2:768x768)
  
adc:

  _unprocessed raw image: (x4/x2:256x256)
  
  _LR: Downsampled input image (x4/x2:64x64)
  
  _org: Original image (same size as _HR, used to calculate loss) (x4:256x256, x2:128x128)
  
  _HR: Output image of the model (_LR image is input) (x4:256x256, x2:128x128)
  
  _SR: Output image of the model (_unprocessed raw image is input) (x4:1024x1024, x2:512x512)

  
