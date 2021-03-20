# Linked-List

Linked List imleplementation in Javascript to use in projects

// Class usage

  let linkedList = require('./linkedlist');

let ll = new linkedList();

ll.isEmpty(); // true

// Adding an element to linked list
ll.add('a');
ll.add('b');
ll.add('c');
ll.add('d');
ll.add('e');

ll.size_of_list(); // 5

// index of an element
ll.indexOf('b'); // 1

// inserting an element 'aa' at index 1 between element 'a' and 'b'
ll.insertAt('aa', 1);

ll.printList(); // a aa b c d e

// remove an element from Linkedlist
ll.removeElement('aa');

ll.printList(); // a b c d e

ll.removeFrom(4);

ll.printList(); // a b c d
