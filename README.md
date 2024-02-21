# droid_oct_envelope

This project contains two different octuple complex envelope patches:
- Quad_ADSR_CV.ini , the parameters of each envelope can be influenced with CV
- Quad_ADSR_VO.ini , the envelope level can be set by CV. This can be used to create envelopes for filters that respond V/O signals.


# How to use Quad_ADSR_CV.ini
![alt text](patch_cv.png)

- Select which envelope you wish to adjust with the buttons Env1 ... Env8
- Select what triggers the selected envelope
    - Trig1 ... Trig4 are the the gates inputs of the Droid
    - clk ... clk*5 are the clock and its multiple frequencies
- Select the parameters of the envelope
    - Static is the default parameters
    - CV1 ... CV4 is the influence of the CV input on the parameters
    - The slider set the individual parameters or the CV influence
- In addition to traditional ADSR envelopes, one can blend a lfo with the envelope
    - select the shape of the LFA with the buttons Square ... Cos
    - The parameter LFO level define the amplitude of the LFO
    - LFO freq defines the frequency of the envelope
    - LFO attach defines how fast the envelope is blended into the signal.
- The clocks are controled with
    - Tempo pot to adjust the speed
    - Play to let the clock run
    - Stop that stops the clock, while the button is pressed down it also pull the Reset output high


# How to use Quad_ADSR_CV.ini
![alt text](patch_vo.png)


- Select which envelope you wish to adjust with the buttons Env1 ... Env8
- Select which gate Gate1 ... Gate4 triggers the selected envelope
- Select if the level of the envelope is defined by V/O1, .... , V/O4. If the level should be a constant, select V/O--
- In addition to traditional ADSR envelopes, one can blend a lfo with the envelope
    - select the shape of the LFA with the buttons Square ... Cos
    - The parameter LFO level define the amplitude of the LFO
    - LFO freq defines the frequency of the envelope
    - LFO attach defines how fast the envelope is blended into the signal.

