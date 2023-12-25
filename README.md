- Input shape: 512 x 512 x 3 (Color Image - RGB)
- Object Classes: \[ 'Origin', 'Recaptured' ]
- Output: \[a,b]
  - a: Probability of class 'Origin'
  - b: Probability of class 'Recaptured'

- Model version:
  - v1: Model with 3 branchs without resizing layers
  - v2: Model with 3 branchs with resizing layers
  - v3: Model with 4 branchs with resizing layers
