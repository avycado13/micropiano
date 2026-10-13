# micropiano

A piano as a data uri using browser oscillator APIs. basically when you hit a key on it, it calculates the pitch of the note you clicked using the formula `const f = (midi) => 440 * 2 ** ((midi - 69) / 12);` where each key has a midi number. It then oscillates at that pitch with a gradual volume curve to 0.
