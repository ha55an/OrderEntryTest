# Order Entry Dialog Test
## UI SASS Test

* Converted illustrator file of an Order Entry Dialog. 
* Built using only HTML and SASS/LESS.

### Build Notes:
*	I have assumed the “OFFER”, “Good Till Date” and “Good Till Time” are also input fields as they contain values that seem to need overriding.
*	For the sake of clarity, I have assumed that by active state – what the instruction meant is the html element state of focussed. (Active state in HTML also refers to the state while an element is being pressed/clicked, not before or after.)
    *	I have applied styling very similar to the “BID” input focussed state for the focussed states for these input fields (and associated labels). 
    *	For the input fields, I implemented the placeholder values with the html attribute “value” rather than the attribute I would have preferred, “placeholder”. This is because Internet Explorer clears the placeholder attribute value when focussed unlike Firefox and Chrome. This would not have matched the design for Internet Explorer.
*	I changed the order of the input fields with their respective label elements so that the labels could change colour dependant on their input fields state using only CSS. 
*	The button colours for “Bid”, “Submit Both”, and “Offer” did not match the button colour guide below the mock-up in the Illustrator file. I took the buttons colour guide rather than the mock-up as the “truth”.
*   I applied the same styling for both toggle states "YES" and "NO". They could be different.
*	Browsers use different techniques to render type. This appears to cause some difference between the results visually even though the browsers seem to report the same sizing. This could be investigated further if a closer to identical result is required.
*	For comparison, the docs folder contains screenshots of the results from Chrome, Firefox and Internet Explorer along with the original design exported from Illustrator.


Created by Hassan Zamir on 23/8/2016, updated on 1/9/2016.
