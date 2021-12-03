# ns3.30-dvhop
Distance-Vector Hop updated from ns2.20 to ns3.30, adapted from Pixki.

Place dvhop-example.cc, dvhop-critical.cc, and wscript into ns3/src/dvhop/examples

Place all other files into ns3/src/dvhop/model

All nodes calculate their positional info based on packets recieved from beacon nodes.
