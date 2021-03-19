# quantum
Quantum Demos
The best way to run these notebooks is by using the IBM Quantum Experience. Follow these instructions to do so.

Go to the IBM Quantum Experience at https://quantum-computing.ibm.com/ and log in. If you haven't done so before, you will need to create an account.

Once you have logged into the IBM Quantum Experience, click the Quantum Lab button on the left navigation bar shown in the image here: image.

Click the New Notebook button shown in the image here: image

In the new notebook, paste the following instructions in the empty cell as shown in the image here:

!rm -r ieee-quantum-week-2020/
!git clone https://github.com/aasfaw/ieee-quantum-week-2020.git
!mv ieee-quantum-week-2020/* .
!rm -r ieee-quantum-week-2020/ LICENSE
image

Press Shift+Enter. It will take a moment for the instructions that you have pasted to execute. When they complete, you should get a message Unpacking objects: 100%, done. as shown in the image here: image

Once your instructions have executed, go back to the Quantum Lab page by clicking the Quantum Lab button on the left navigation bar shown in the image here: image

Now, you can click on one of the numbered notebooks to open it, as shown in the image here: image
