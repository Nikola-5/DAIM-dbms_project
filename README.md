# DAIM-dbms_project
Implementation of the Distance Aware Influence Maximization Problem

There are two c++ files in this project. MIA complete represents the implementation of the MIA algorithm that was a basis for our implementation paper algorithm. The other one, Complete_Program_final represents the implementation of the algorithm proposed in our implementation paper. 

Here is how to compile on of the files:

```
g++ -std=c++14 -o daim Complete_Program_final.cpp

```

And this is how you can run it:

```
./daim

```

Finally, to change how propagation probabilities are calculated adjust this part of the code:

```
        // Set propagation probability model (WC or TC), choose one model a time during experiment
        setWCModel (networkGraph);
        cout << "Using WC model: " << endl;
        //setTCModel (networkGraph); // <-remove comment if elment this, and comment the other
        //cout << "Using TC model: " << endl;
```
