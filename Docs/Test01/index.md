# Table Cases: Empty column/Row

## Normal table

<table>
  <thead>
    <tr>
      <th>Normal table</th><th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1_Help</td><td>Display the help window.</td>
    </tr>
    <tr>
      <td>Close</td><td>Closes a window</td>
    </tr>
  </tbody>
</table>

## Empty Row
### The first row is empty

<table>
  <thead>
    <tr>
      <th</th><th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1_Help</td><td>Display the help window.</td>
    </tr
    <tr>
      <td>Close</td><td> Closes a window</td>
    </tr>
  </tbody>
</table>

### The second row is empty

<table>
  <thead>
    <tr>
      <th>Normal table</th><th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></td><td></td>
    </tr>
    <tr>
      <td>Close</td><td>Closes a window</td>
    </tr>
  </tbody>
</table>

### The first and second row are empty

<table>
  <thead>
    <tr>
      <th></th><th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></td><td></td>
    </tr>
    <tr>
      <td>Close</td><td>Closes a window</td>
    </tr>
  </tbody>
</table>

## Empty Column
### The first column is empty
|  |Table header 2 |
| ------------- | ----------- |
|      |Cell |
|      |   Cell |

### The last column is empty
|  |Table header 2 | |
| ------------- | ----------- |---|
|  Cell    |Cell |  |
|      |   Cell |  |

## Empty Column & Row 
### Empty Column & Row

|  | | |
| ------------- | ----------- |---|
|  Cell    |Cell |  |
|      |   Cell |  |

### Empty Column & Row

|  | head2 | head3|
| ------------- | ----------- |---|
|      | |  |
|      |   Cell |  |
