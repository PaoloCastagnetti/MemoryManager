# MemoryManager

### Members
Paolo Castagnetti <br />
Andrea Mocellin <br />
Marco Pastrello <br />

### Project Requirements
We have to design and develop a general purpose Memory Management System in C++ as a project for our Advanced C++ course of the Master in Computer Game Development of Verona (2022-2023).

The Memory Manager utilizes two different "underlying" allocators: one based on Andrei Alexandrescu's SmallObjectAllocator, for the allocation of small objects, and the other built upon a Black-Red Tree structure for the allocation of bigger objects. The project has custom allocation/deallocation functions that differentiate between the sizes of memory blocks and calls the proper underlying allocator.

SmallObjectAllocator: Paolo Castagnetti <br />
BR Tree and bigger object allocator: Marco Pastrello <br />
Allocation/Deallocation functions: Andrea Mocellin <br />
