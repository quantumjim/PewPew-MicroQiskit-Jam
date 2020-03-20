# PewPew + MicroQiskit

If you want to do some quantum computing, you'll need some software and some hardware. The best software is [Qiskit](https://qiskit.org), an open-source Python-based framework. The best place to get your hands on hardware is the [IBM Quantum Experience](https://quantum-computing.ibm.com).

But maybe all that's a little too advanced for your first step into this new world...

Instead of using the most well-developed framework for quantum computing &mdash; full to the brim with fancy features &mdash; maybe something more minimal is best to start off with. And instead of using trying to push the world's most advanced quantum devices to their limits, it's best to have a more limited scope for your first quantum programs. That will make it possible to use a simple emulator rather than a real device, which makes things easier.

With these ideas in mind, we bring you [MicroQiskit](https://github.com/qiskit-community/MicroQiskit). This let's you play with the basics of quantum computing and familiarize yourself with the syntax of Qiskit, all in the most straightforward way possible.

Now the question is: what will be your first attempt at writing a quantum program? My suggestion is to make a game! Just try using one or two qubits to implement a simple game mechanic. To get a bit of context on why this is a good idea, check out the following.

* [Making games with quantum computers](https://medium.com/@decodoku/games-computers-and-quantum-84bfdd2c0fe0)

The usual way to make a game is using a powerful engine like [Unity](https://unity.com/) or [Godot](https://godotengine.org/). Some instead prefer to use a low-fi engine like [PICO-8](https://www.lexaloffle.com/pico-8.php): either because it levels the playing field between experts and newbies, or just because it is fun. Given that our aim is to learn to use Qiskit/MicroQiskit, we'll go the low-fi route. Specifically, we'll use an extended version of the [PewPew](https://github.com/pewpew-game/) game engine, implemented using [Pygame](https://github.com/pewpew-game/). Everything you need to develop, play and share games made with this engine is in the link below.

* [PewPew + MicroQiskit on Repl.it](https://repl.it/@quantum_jim/PewPewMicroQiskit)
