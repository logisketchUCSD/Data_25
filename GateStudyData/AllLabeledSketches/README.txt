These are all the sketches from the Circuit User Study, which is described in the following paper:

The Effect of Task on Classification Accuracy: Using Gesture Recognition Techniques in Free-Sketch Recognition.  Martin Field, Sam Gordon, Eric Peterson, Raquel Robinson, Thomas Stahovich, Christine Alvarado.    Computers and Graphics, Special Issue on Sketch-Based Interfaces and Modeling. 34(5) October 2010.  (Conference version available here: http://www.cs.hmc.edu/~alvarado/papers/sbim09.pdf)

Please see that paper for a description of how these sketches were collected. 

They have been labeled, where each shape has been given a label. 

Sub-shapes and gate parts have NOT been labeled.

The copy and synthesize task sketches (CPY and EQN) have been "cleaned"
during which small strokes (less than a few points, or having a bounding box 
area that is very small) have been removed. Also removed are strokes that 
were meant to be erased (were scribbled out). Also removed are portions 
of strokes that were the result of digitizer error that left a long tail at 
the end of the stroke.

The filename can be interpreted as follows:
  USERID_TASK_SCHOOL_TorP.labeled.xml
where:
  USERID = the user's ID number
  TASK = single gate drawing (AND, OR, etc), copying (COPY) or equation synthesis (EQ1, EQ2)
  SCHOOL = Harvey Mudd (HMC) or UC Riverside (UCR)
  TorP = Wacom tablet with paper overlay (P), or Tablet PC (T)
  
The XML format is described here: http://rationale.csail.mit.edu/ETCHASketches/format/