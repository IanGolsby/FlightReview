# FlightReview

Considerations:

Will this involve adding hardware?

  If so, we must consider weight and balance of the hardware, as well as its physical control. Heavy additions or masses placed far from CoG on the aircraft will alter flight stability, potentially leading to danger to pilot, onlookers, the aircraft, and other airborne entities. If the hardware addition has any ability to control the craft, it must be under thorough failsafing so it cannot do so unexpectedly and can be immediately remotely shut down. Hardware should also ideally be inexpensive and easy to install, so that this project is still easily accessible to other pilots.

  If there is no hardware, we only have to consider software related issues, which will still be relevant in the case of adding hardware. Altering the software of the Flight Controller must be done carefully if at all, because this could impact its processing speed (which would interfere with operation of its internal control systems), and any errors could lead to very unexpected behaviors from the craft.

How do we test these?

  For hardware weight and balancing, some napkin level math can be done to show whether a system should cause any issues, and it can be more thoroughly tested by simply flying in a controlled environment (closed off but large and empty space) and observing how the craft behaves. Software can be tested by running it on the ground and performing as much testing on it as possible without flying, and then performing more testing in a controlled environment again. Component diagrams of hardware will also be carefully analyzed to determine the plausibility of any negative impact on the flight controller's inputs or processing.
