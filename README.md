# sbx-worker
In charge of hosting virtual machines, it encapsulates the logic to create and manage virtual hardware and perform cleanup operations as well as executing tasks required by the control module. It will interact with the control module through gRPC, the implementation will be in Java to leverage existing XPCOM libraries.
