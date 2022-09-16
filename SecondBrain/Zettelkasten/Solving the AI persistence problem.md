10/4/22
- [ ] Somehow, the state of the synapses has to be stored
- [ ] I could probably save all of them to the AI_ID object and them use pickle, but in that case, I would have to change how the neurons and synapses are accessed
- [ ] Perhaps I could continue the Vector translation of the AI, as it would be easier to save an make computations
- [ ] I have to store in a file, and them load it in an object or dictionary of some sort
13/4/22
- [ ] Well, I just found a much, much better way which is to create a database on sqlite3 with the neurons updated when the action is equal to the expected, and a database with the working neurons untill a result happens
- [ ] I tried it with zip ziles but it was a complete disaster since it would take about 24 hours to zip a file with all the neurons after pickle
- [ ] 
[[AI]], [[Computing]], 