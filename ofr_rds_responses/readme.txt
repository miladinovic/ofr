The textual data in the directory represent the output of the intermediate step of raw image data processing.
The files are generated with the specific algorithm (described in detail in the article) that finds the centre of the pupil and the centre of the marker. The input data consisted of the 3 photograms acquired at the t0=0ms, t1=80ms and t2=160ms. The period t0-t1 represents the fixation time, whereas, the time t1-t2 represents the eye-movement period induced by the stimulus.

		Trial Codes:
			1st digit: Direction of motion of grating 
				1 - rightward/upward
				2 - leftward/downward
			2nd digit: Axis of motion
				1 - Horizontal
				2 - Vertical
			3rd digit: 0  
			4th digit: 0 
			5th digit: 0

		"11000" "Right"
		"21000" "Left"
		"12000" "Up"
		"22000" "Down"

The text file have the following structure:


trial number input_img_number1	input_img_number2 trial_code pupil_displacement_x pupil_displacement_y marker_displacement_x marker_displacement_y eye_displacement_x eye_displacement_y pulil_size_change
