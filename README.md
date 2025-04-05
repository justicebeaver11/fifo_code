# fifo_code

FIFO (First-In, First-Out) memory is a type of buffer or queue that stores data in the order it was received and outputs it in the same order. Synchronous FIFO means that both read and write operations are synchronized to the same clock.

🧩 Component	Description <br>
Data Input	Where new data enters (write side). <br>
Data Output	Where stored data is read out. <br>
Write Pointer	Points to the next location to write. <br>
Read Pointer	Points to the next location to read. <br>
Memory Array	The actual storage area (like a RAM block). <br>
Control Logic	Manages pointers and status flags. <br>

🚦 Control Signals: <br>
Signal	Description <br>
write_en	Enables data to be written. <br>
read_en	Enables data to be read. <br>
full	Indicates FIFO is full (no writes allowed). <br>
empty	Indicates FIFO is empty (no reads allowed). <br>
reset	Clears the FIFO and resets pointers. <br>
