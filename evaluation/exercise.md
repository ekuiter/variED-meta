## Collaborative Feature Modeling - Sample exercise

- To solve this exercise, two collaborators are required. You will both edit the *Car* product line, but with different ideas and intentions.
- Please visit the following link to begin: http://[...]/#/Examples/Car <br>
  You can also open the feature model manually with `Tools > Command Palette > Join collaborative session > Examples > Car`.
- Make sure in the top right corner that you and your partner are undisturbed by others (as this instance of the tool is public).
- Assign one collaborator **role A** and the other **role B**. These will be used in the tasks below.
- While editing, you are free to discuss anything with your partner (but you don't have to).
- In solving these tasks, you are allowed to use all operations that the editor provides (including restructuring of subtrees or modification of constraints).
- After this exercise, please use the survey form to share your impressions.
  If you encounter unexpected problems (e.g., something you consider a bug), you may wish to include the current timestamp so we can trace the root of the issue.

### Role A

- New cars with innovative functionalities (i.e., features) shall be added to the product range.
  To this end, you are to model new features in the *Car* product line in an appropriate fashion.
  - Here are some examples for possible new features: electric engine, wifi, internet radio, surround sound, hands-free headset, park distance control, alarm system
- In addition, improve the feature model in such a way that it models the following facts more accurately.
  - We know from sales that
    - only few cars are equipped with a CD player anymore,
    - without exception, every car has a carbody and a gearbox
  - When analyzing the model, we also find that Bluetooth is actually a radio port, just as USB or a CD player.  

### Role B

- New cars with innovative functionalities (i.e., features) shall be added to the product range.
  To this end, you are to model new features in the *Car* product line in an appropriate fashion.
  - Here are some examples for possible new features: electric engine, wifi, internet radio, surround sound, hands-free headset, park distance control, alarm system
- In addition, improve the feature model in such a way that it models the following facts more accurately.
  - We know from sales that
    - the *GearboxTest* feature is deprecated and not used any more,
    - many customers want to install not only one, but several maps (*DigitalCards*) in their navigation system,
    - some customers do not need Bluetooth at all (but some do)
  - When analyzing the model, we also find that navigation is actually independent of the car radio.