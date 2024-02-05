# **Lem-in**

This project involves creating a program, `lem-in`, that simulates a digital version of an ant farm. The goal is to find the quickest path for a given number of ants to traverse a colony consisting of rooms and tunnels.

## **How It Works**

1. **Input:** The program reads input from a file provided as a command-line argument. This file describes the layout of the ant farm, including information about rooms, tunnels, and the number of ants.

2. **Ant Farm Setup:** You create an ant farm with rooms and tunnels. The ants start in the room marked as ##start, and the objective is to guide them to the room marked as ##end using the shortest path.

3. **Challenge:** The task is not only to find the shortest path but also to handle various invalid or poorly-formatted inputs. This includes cases where there are no paths between ##start and ##end, self-linking rooms, incorrect numbers of ants, duplicated rooms, links to unknown rooms, invalid coordinates, and more.

4. **Output Format:**
    - The program must display the results on the standard output in the following format:

    ```
    number_of_ants
    the_rooms
    the_links
    ```
    - Example:

    ```
    ##start
    1 23 3
    2 16 7
    #comment
    3 16 3
    4 16 5
    5 9 3
    6 1 5
    7 4 8
    ##end
    0 9 5
    0-4
    0-6
    1-3
    4-3
    5-2
    3-5
    #another comment
    4-2
    2-1
    7-6
    7-2
    7-4
    6-5
    ```    

5. **Example Representation:**

   // add some photo for example

## **Error Handling**
In case of invalid data formats, the program will return an error message, for example:

- `ERROR: invalid data format, invalid number of Ants`
- `ERROR: invalid data format, no start room found`

Feel free to customize error messages to provide more specific information about the encountered issues.

## **Usage**

// add comand for run

## **Authors**
 - [Tolganay](https://github.com/Tolkynbayeva?tab=overview&from=2024-02-01&to=2024-02-05)
 - [Rick](https://github.com/RickDred?tab=overview&from=2024-02-01&to=2024-02-05)   
