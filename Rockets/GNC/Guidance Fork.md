**Libraries:**
OriMath
  Vec3
    add sub mult div
    norm length dot cross
  Quaternion
    mult
    norm conj
    euler2quat quat2euler
    vecrot
    imusim
    getvecguidance
  Misc
    clamp
    r2d d2r
NaviMath
  DOF6
    addforce
    addtorque
    update
      angvel
      ori euler
      globalacc globalgrav
      vel
      pos (pos clamp check)
      reset (acc and angacc)
  Simulation
    update (time += timestep, interations)
  PID
    calculatepid
    changesetpoint
    reset
  TVC
    actuate (error, speed, angle)
    gettorque (sideforce)

ThrustCurve
*parses input csv files*

**Main Loop:**



Fork:
Electron GUI

