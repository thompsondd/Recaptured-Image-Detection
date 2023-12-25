- Input shape: 512 x 512 x 3 (Color Image - RGB)
- Object Classes: \[ 'Origin', 'Recaptured' ]


- Model version:
  - v1: Model with 3 branchs without resizing layers
    - Output: \[a,b]
      - a: Probability of class 'Origin'
      - b: Probability of class 'Recaptured'
  - v2: Model with 3 branchs with resizing layers
    - Output: \[a,b]
      - a: Probability of class 'Origin'
      - b: Probability of class 'Recaptured'
  - v3: Model with 4 branchs with resizing layers
    - Output: \[b,a]
      - a: Probability of class 'Origin'
      - b: Probability of class 'Recaptured'
