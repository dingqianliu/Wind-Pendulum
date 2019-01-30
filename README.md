# A robust inverted pendulum control system
This is a course project for the Honors Program’s electronic design course; I led the team and was incharge of algorithm design and implementation.

**Problem:** Our goal was to build an inverted pendulum whose trajectory formsan almost straightlineprojected to the ground. Under interference, it should be able to readjust itself agilely.

**Design:** We used a feedback system via PID and Kalman Filter to detect interference and correctthe motion; it reduces the readjustment latency by5×over the open-loop implementation.
