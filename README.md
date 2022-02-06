# Data-Analysis-SPSS-Modeler-SAS

## Overview:

This repository is to store my topics' experience using the IBM SPSS Modeler and IBM SAS.

## Tools:

- IBM SPSS Modeler

- IBM SAS

## Content:

### Unit 2 - Introduction to SPSS Modeler

### Exercise 1: Tasks and Results

#### Task 1. Create a stream that reads data from IBM SPSS Statistics and exports data to Microsoft Excel (dry run).

• Place the following nodes on the stream canvas:
• Statistics File (Sources palette)
• Select (Record Ops palette)
• Sort (Record Ops palette)
• Derive (Field Ops palette)
• Histogram (Graphs palette)
• Derive node (Field Ops palette)
• Distribution (Graphs palette)
• Excel (Export palette)

Ensure the nodes are connected to form a stream.

The results appear similar to the following picture

![Ex 1 - Task 1](https://user-images.githubusercontent.com/70437668/150724889-9d17dcd3-ee19-4c24-8d82-21cf7c2a815e.jpg)

#### Task 2. Modify the stream.

• Delete the second Derive node.
• Delete the Distribution node.
• Connect the Derive node to the Excel node.
• From the Export palette, add a Statistics Export node downstream from the Derive node.
• Right-click the Derive node and add a comment such as new field is derived.
• Right-click an empty area on the stream canvas, and add a comment stating the author and date.

The stream should appear similar to the following

![Ex 1 - Task 2, 3](https://user-images.githubusercontent.com/70437668/150724974-c83fa672-b7c8-4bef-b638-bfc6888a33c3.jpg)

#### Task 3. Save the stream.

• From the File menu, click Save Stream, and type MyExercise.str and then click Save.

The title bar will show the file name.

#### Task 4. Create a new stream by copying and pasting from an existing stream.

• Select all nodes (for example, by drawing a rectangle that includes all nodes, by clicking Ctrl+A, or by clicking the Edit menu, and then choosing Select All).
• Copy the selected nodes.
• From the File menu, click New Stream to open a new window.
• Paste the content of the clipboard to the stream canvas.
• Insert a Sample node between the Derive node and the Statistics Export node.

The stream should appear similar to the following picture after Task 5.

#### Task 5. Make the stream neat by using a SuperNode.

• Select the Select and Sort node (for example, by using the mouse to drag a rectangle around them).
• Right-click one of the selected nodes, and then click Create SuperNode from the context menu.
• Right-click the SuperNode, select Rename and Annotate from the context menu, click the custom option if necessary, and then type data preparation. (Alternatively, edit the SuperNode and click the Annotations tab.)

![Task 4, 5](https://user-images.githubusercontent.com/70437668/150725157-627610a1-3442-4b7f-90b5-8a61be89ce70.jpg)

#### Task 6. Generate a Select node from Table output.

• From the File menu, click Open Stream, navigate to the C:\Training\0A008\02-Introduction_to_IBM_SPSS_Modeler\Start folder, open unit_02_exercise_1_start, and then run the Table node.
• In the Table output window, click the yes value in the HAS_RECEIVED_TEST_MAILING column, click the Generate menu, and then click Select Node ("And").
• Insert the generated node named (generated) between the Excel node and Table node. Also, rename the generated node to in test mailing.

The results appear similar to the following:

![Ex 1 - Task 6](https://user-images.githubusercontent.com/70437668/150725201-ce75e40e-d7ae-43f7-8570-b734e05fa6e4.jpg)

Run the Table node. This will show that 10,000 records are selected.

#### Task 7. Further record selections.

Next, select men and women from the 10,000 customers in the test mailing.

• In the Table output window, use Ctrl-click to select a female and male values, and from the Generate menu, click Select Node ("Or").
• Insert the generated node between the in test mailing node and the Table node, and then rename the node to men, women.

The results appear similar to the following:

![Ex 1 - Task 7](https://user-images.githubusercontent.com/70437668/150725267-34a92557-6bbc-4be7-82d8-16f3b60fc4ef.jpg)

Run the Table node. This will show that there are 9,980 records left.

Task 8. Exit IBM SPSS Modeler.

• From the File menu, click Exit, and then exit IBM SPSS Modeler without saving anything.

You will find the solution results in the C:\Training\0A008\02-Introduction_to_IBM_SPSS_Modeler\Solutions folder.

### Unit 6: Setting the unit of analysis

![Exercise 5 - Phuong Dai Ngo (Liam) - N01427233](https://user-images.githubusercontent.com/70437668/152669124-da7ebc72-bf70-4f74-8442-56263f73c670.jpg)

### Unit 7: Integrating data

![Exercise 6_Unit 7_Phuong Dai Ngo (Liam) - N01427233 - Copy](https://user-images.githubusercontent.com/70437668/152671969-ed306c5f-11e3-44c3-a550-16b1ed380beb.jpg)

