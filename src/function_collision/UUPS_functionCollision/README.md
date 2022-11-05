This demonstrates how function collisions work and also why an implementation contract should never have an unchecked delegatecall that can call random addresses.  If the owner could unknowingly call or be tricked into calling a shady contract that may obfuscate its intentions through function collision.