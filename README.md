problem in Double_track_model: Cannot continue simulation at time ....... error was popping.
Made another 2-track model: - updated 2-track_model 
problem in this was that traction force on each wheel was negative.
Complete double-track model was ready with camber, caster and toe dynamics added in it. Didn't upload the load_data file coz github doesn't allow to add files which are larger than 25 MBs
Added 6 DOF to previous model: 4 from vertical displacement of each suspension and 2 more from rolling and pitching motion of the car
updated_seven_dof_vehicle_model is equipped with proper inputs 
added aerodynamic downforce to the previous model, aerodynamic drag(lateral and longitudinal) were already modeled and also added pitching moment due to the aerodynamic downforce and updated load_data parameters.
