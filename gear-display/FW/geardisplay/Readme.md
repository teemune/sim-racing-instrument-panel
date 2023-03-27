## Changes from SimHub default config:
### Change 7-segment display configuration:
byte g_6c595fontArray[] = {
	// a-b-c-d-e-f-g-dp
  0b11111100, // 0        
  0b01100000, // 1            
  0b11011010, // 2
  0b11110010, // 3
  0b01101010, // 4
  0b10110110, // 5
  0b10111110, // 6
  0b11100000, // 7
	0b11111100, // 8
	0b11110110, // 9
	0b00000000, // OFF empty
	0b11101111, // REVERSE SPEED
};

to

#### Rev1 PCB:
byte g_6c595fontArray[] = {
  // a-b-c-d-e-f-g-dp
  0b11111100, // 0        
  0b01100000, // 1            
  0b11011010, // 2
  0b11110010, // 3
  0b01101010, // 4
  0b10110110, // 5
  0b10111110, // 6
  0b11100000, // 7
  0b11111100, // 8
  0b11110110, // 9
  0b00000000, // OFF empty
  0b11101111, // REVERSE SPEED
};

#### Rev2 PCB:
byte g_6c595fontArray[] = {
  // dp-g-f-e-d-c-b-a
  0b00111111, // 0        
  0b00000110, // 1            
  0b01011011, // 2
  0b01001111, // 3
  0b01110010, // 4
  0b01101101, // 5
  0b01111101, // 6
  0b00000111, // 7
  0b00111111, // 8
  0b01101111, // 9
  0b00000000, // OFF empty
  0b11101111, // REVERSE SPEED
};