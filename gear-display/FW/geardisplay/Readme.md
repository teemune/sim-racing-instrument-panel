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