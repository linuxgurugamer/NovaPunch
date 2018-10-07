The model for this engine is broken for Unity 5.1.

Once someone manages to remake it, I'll be able to restore the engine.

The collision mesh which is used for physics calculations was 
probably directly derived from the visual appearance. This makes 
it too complex and, more importantly concave, as it follows the 
inner contour of the bell, which is not kosher with Unity 5.1, 
just simplify the collision mesh and make sure it has no concavities, 
and it should work fine. 
