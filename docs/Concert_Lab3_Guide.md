# IBM INNOVATION DAY

October 22, 2025

# Zero to Workflow: Create Fast with Low-Code/No-Code Magic

![IBM Innovation Day](./img/image001.png "IBM INNOVATION DAY")

## Where Code Meets Concert – Exercise Guide 3

### 3. Concert Workflows Exercise (Optional)

This workshop will show beginners of the product the value of Concert Workflows by rapidly integrating different tools and orchestrating actions across them using a low-code interface. Users will be able to experience firsthand the various ways a data can be formated and used.
The workshop provides a task to be solved in a workflow by yourself.
Hint are provided to give guidance.
Some concepts like creating variables, assign block, opening a workflow, and the steps to create your workflow is not covered in this workshop. To learn the basics of the platform, please complete [Lab 1](./20250709_Concert_Lab1_Guide.md) first.

#### 3.1	Task description

Create a workflow called **Get books**, the workflow should contain the following steps

1.	Get a list of books

    The book list can be retrieved from the **api_url** [https://softwium.com/api/books](https://softwium.com/api/books) with the **request_method** `GET`

2.  Iterate through the response (list of books)

3.  Look for the number of pages the book has

4.  Create 2 arrays based on the page count of the books

    One that called **short_books** with book that have 400 or less pages and one called **long_books**

5. The arrays should be returned by workflow and written to the logs.


    This illustrates how data can be retrieved, processed, and how to orchestrate various actions together.

#### 2.2 Hints

Hints can be found [here](./Concert_Lab3_Hints.md)
