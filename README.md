# Road-to-Quantum-Computing
A documented journey of me learning Quantum Computing during the Summer of 2021

## Quantum computing for the very curious

Can be read here: https://quantum.country/qcvc
It requires an account to be most effective, but offers repeating memory cards that question your learnt knowledge, also remembers you trough emails that you should come back and do a review, which helps in memorizing everything.

> Learning this material is challenging. Quantum computing and quantum mechanics are famously “hard” subjects, often presented as mysterious and forbidding. If this were a conventional essay, chances are that you’d rapidly forget the material. But the essay is also an experiment in the essay form. As I’ll explain in detail below the essay incorporates new user interface ideas to help you remember what you read. That may sound surprising, but uses a well-validated idea from cognitive science known as spaced-repetition testing. More detail on how it works below. The upshot is that anyone who is curious and determined can understand quantum computing deeply and for the long term.

## List of Quantum gates

![Quantum Gates](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Quantum_Logic_Gates.png/1024px-Quantum_Logic_Gates.png)
_Source: https://en.wikipedia.org/wiki/Quantum_logic_gate_

# Setting up Qiskit

This setup is for `WSL2` under Windows. As I am running `ubuntu` there, this should be the same for most linux distros, but YMMV.

To be able to experiment and work with Quantum Algorithms, we need an adequate environment. This is a simple guide to set everything up:

- To keep our workplace clean, we use `anaconda` for virtual environments
    - Use this guide to install `anaconda` over the CLI:
    https://educe-ubc.github.io/conda.html
- Create a virtual environment with `conda create -n NAME python=3` (python=3 is a requisite by qiskit)
- install qiskit using
    - `pip install qiskit`
    - `pip install qiskit[visualization]`
- Pick your favourite IDE and get going!

# Videos of fundamentals:

_Linear algebra (Playlist)_ 

https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab


_Complex (imaginary) number fundamentals_ 

https://www.youtube.com/watch?v=5PcpBw5Hbwo



