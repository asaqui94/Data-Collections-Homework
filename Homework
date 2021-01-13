{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Data Collections 2 (Dictionaries, Sets) and Importing Modules"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Tasks Today:\n",
    "\n",
    "1) Dictionary <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; a) Declaring (key, value) <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; b) Accessing Values <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; ------ Exercise #1 - Print the eye color of each person in a double nested dict <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; c) Adding New Pairs <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; d) Modifying Values <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; e) Removing Key, Value Pairs <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; f) Looping a Dictionary <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; g) Looping Only Keys <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; h) Looping Only Values <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; ------ Exercise #2 - Create a Function that Prints All Key Value Pairs within a print .format()  <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; i) sorted() <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; j) Lists with Dictionaries <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; k) Dictionaries with Lists <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; l) Dictionaries with Dictionaries <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; ------ Exercise #3 - Write a Function that asks someone's name and address, and then stores that into a dictionary, which prints all names and addresses after they're done putting information in...  <br>\n",
    "2) Dictionaries vs. Lists (over time)<br>\n",
    "3) Set <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; a) Declaring <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; b) .add() <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; c) .remove() <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; d) .union() <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; e) .intersection() <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; f) .difference() <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; g) Frozen Set <br>\n",
    "4) Modules <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; a) Importing Entire Modules <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; b) Importing Methods Only <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; c) Using the 'as' Keyword <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; d) Creating a Module <br>\n",
    "5) Exercises <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; a) Build a Shopping Cart <br>\n",
    " &nbsp;&nbsp;&nbsp;&nbsp; b) Create Your Own Module <br>"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Dictionary <br>\n",
    "<p>A collection of data with 'key:value' pairs. Dictionaries are ordered as of Python 3.6</p>"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Declaring (key, value)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [],
   "source": [
    "# keys have to be unique\n",
    "# keys CAN be numbers or strings\n",
    "\n",
    "d_1 = {}\n",
    "\n",
    "# OR \n",
    "\n",
    "d_2 = dict()\n",
    "\n",
    "# Dictionary with keys/values\n",
    "d_3 = {\n",
    "    'dave':'255 Main Street',\n",
    "    'sean':'522 1st Street',\n",
    "    0:'This is a value for the key of 0'\n",
    "}"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Accessing Values"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'This is a value for the key of 0'"
      ]
     },
     "execution_count": 4,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# dict[key]\n",
    "\n",
    "d_3['dave']\n",
    "d_3[0] # not an index"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## In-Class Exercise #1 - Print a formatted statement from the dictionary below <br>\n",
    "<p>The output should be '2018 Chevrolet Silverado'</p>"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 15,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      " My favorite car is 2018 Chevrolet Silverado\n"
     ]
    }
   ],
   "source": [
    "# use the dict below\n",
    "truck = {\n",
    "    'year': 2018,\n",
    "    'make': 'Chevrolet',\n",
    "    'model': 'Silverado'\n",
    "}\n",
    "\n",
    "print(f\" My favorite car is {truck['year']} {truck['make']} {truck['model']}\") # be aware of quotes"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Adding New Pairs"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'dave': '255 Main Street',\n",
       " 'sean': '522 1st Street',\n",
       " 0: 'This is a value for the key of 0',\n",
       " 'bob': '151 Main Street'}"
      ]
     },
     "execution_count": 16,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# dict[key] = value\n",
    "\n",
    "d_3['bob'] = '151 Main Street'\n",
    "\n",
    "d_3"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Modifying Values"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 17,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'dave': '255 Main Street',\n",
       " 'sean': '522 1st Street',\n",
       " 0: 'This is a value for the key of 0',\n",
       " 'bob': '151 Main Street Chicago,IL'}"
      ]
     },
     "execution_count": 17,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# dict[key] = value\n",
    "\n",
    "# Create a placeholder for current data inside of 'bob'\n",
    "placeholder = d_3['bob']\n",
    "\n",
    "d_3['bob'] = f'{placeholder} Chicago,IL'\n",
    "d_3"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Removing Key, Value Pairs"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 18,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'dave': '255 Main Street',\n",
       " 'sean': '522 1st Street',\n",
       " 0: 'This is a value for the key of 0'}"
      ]
     },
     "execution_count": 18,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# del dict[key]\n",
    "\n",
    "del d_3['bob']\n",
    "\n",
    "d_3"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Looping a Dictionary"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 19,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "dave 255 Main Street\n",
      "sean 522 1st Street\n",
      "0 This is a value for the key of 0\n"
     ]
    }
   ],
   "source": [
    "# .items()\n",
    "# a, b, c = 1, 2, 3\n",
    "# print(a)\n",
    "# print(b)\n",
    "# print(c)\n",
    "\n",
    "for key, value in d_3.items():\n",
    "    print(key,value)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Looping Only Keys"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 20,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "dave\n",
      "sean\n",
      "0\n"
     ]
    }
   ],
   "source": [
    "# .keys()\n",
    "# for i in d_3.keys():\n",
    "    # print(i)\n",
    "\n",
    "for key in d_3.keys():\n",
    "    print(key)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Looping Only Values"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 21,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "255 Main Street\n",
      "522 1st Street\n",
      "This is a value for the key of 0\n"
     ]
    }
   ],
   "source": [
    "# .values()\n",
    "\n",
    "for value in d_3.values():\n",
    "    print(value)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## In-Class Exercise #2 - Create a Function that Prints All Key Value Pairs within a print .format() <br>\n",
    "<p><b>Output should be:</b><br>\n",
    "Max has blue eyes<br>\n",
    "Lilly has brown eyes<br>\n",
    "Barney has blue eyes<br>\n",
    "etc.\n",
    "</p>"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 28,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Max has blue eyes.\n",
      "Lilly has brown eyes.\n",
      "Barney has blue eyes.\n",
      "Larney has brown eyes.\n",
      "Ted has purple eyes.\n"
     ]
    }
   ],
   "source": [
    "# use the dict below\n",
    "\n",
    "people = {\n",
    "    'Max': 'blue',\n",
    "    'Lilly': 'brown',\n",
    "    'Barney': 'blue',\n",
    "    'Larney': 'brown',\n",
    "    'Ted': 'purple'\n",
    "}\n",
    "\n",
    "def descript():\n",
    "    for key, value in people.items():\n",
    "        print(f\"{key} has {value} eyes.\")\n",
    "descript()        "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### sorted()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 39,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[('Barney', 'blue'), ('Larney', 'brown'), ('Lilly', 'brown'), ('Max', 'blue'), ('Ted', 'purple')]\n",
      "blue\n",
      "\n",
      " ['Barney', 'Larney', 'Lilly', 'Max', 'Ted']\n",
      "Barney\n",
      "\n",
      " ['blue', 'blue', 'brown', 'brown', 'purple']\n",
      "purple\n"
     ]
    }
   ],
   "source": [
    "# sorts variables in order\n",
    "# sorted(dict.values()) or dict.keys() or dict.items()\n",
    "\n",
    "print(sorted(people.items()))\n",
    "all_items = sorted(people.items())\n",
    "print(all_items[0][1])\n",
    "\n",
    "print('\\n', sorted(people.keys()))\n",
    "all_keys = sorted(people.keys())\n",
    "print(all_keys[0])\n",
    "\n",
    "print('\\n', sorted(people.values()))\n",
    "all_values = sorted(people.values())\n",
    "print(all_values[-1])"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### List with Dictionaries"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Barbara\n"
     ]
    }
   ],
   "source": [
    "names = ['Dave', 'Randy', 'Greg', {'random_guy':'Robert', 'random_girl':'Barbara'}]\n",
    "print(names[3]['random_girl']) # value of Barbara is only accessible by its key"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Dictionaries with Lists"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 43,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "smith\n",
      "smith\n"
     ]
    }
   ],
   "source": [
    "# be careful when using numbers as keys in dictionaries, don't confuse them with indexes\n",
    "random_data ={\n",
    "    'list1': [54,7,11],\n",
    "    2: ['smith'],\n",
    "}\n",
    "\n",
    "print(random_data[2][0])\n",
    "\n",
    "for value in random_data[2]: # looping through list in dictionary\n",
    "    print(value)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Dictionaries with Dictionaries"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 45,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "5.99\n"
     ]
    }
   ],
   "source": [
    "# to get values, must traverse through keys\n",
    "food_dict = {\n",
    "    'ice_cream': {\n",
    "        'chocolate': 2.99,\n",
    "        'vanilla': 3.99,\n",
    "        'oreo': 5.99,\n",
    "    }\n",
    "}\n",
    "print(food_dict['ice_cream']['oreo'])"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Dictionaries vs. Lists (over time) Example of RUNTIME\n",
    "### When inputting values in a Dictionary vs List"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 46,
   "metadata": {},
   "outputs": [],
   "source": [
    "import time\n",
    "\n",
    "\n",
    "# generate fake dictionary\n",
    "d = {}\n",
    "\n",
    "for i in range(10000000):\n",
    "    d[i] = 'value'\n",
    "    \n",
    "\n",
    "# generate fake list\n",
    "big_list = [x for x in range(10000000)]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 47,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "value\n",
      "Elapsed time for dictionary: 0.0008952617645263672\n",
      "9999999\n",
      "Elapsed time for list: 0.8136439323425293\n"
     ]
    }
   ],
   "source": [
    "# tracking time for dictionary\n",
    "start_time = time.time()\n",
    "\n",
    "print(d[9999999])\n",
    "\n",
    "end_time = time.time() - start_time\n",
    "\n",
    "print('Elapsed time for dictionary: {}'.format(end_time))\n",
    "\n",
    "\n",
    "# tracking time for list\n",
    "start_time = time.time()\n",
    "\n",
    "for i in range(len(big_list)):\n",
    "    if i == 9999999:\n",
    "        print(i)\n",
    "\n",
    "end_time = time.time() - start_time\n",
    "\n",
    "print('Elapsed time for list: {}'.format(end_time))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Exercise #3 - Write a Function that asks someone's name and address, and then stores that into a dictionary, and continues to do so until they choose to 'quit'. Once they quit, the program should print all names and addresses. <br>\n",
    "<p>\n",
    "<b>Proper steps:</b><br>\n",
    "step 1: write a function that takes in information and stores it in a dictionary<br>\n",
    "step 2: define an empty dictionary to work with<br>\n",
    "step 3: create our loop, which asks the user for information until they quit<br>\n",
    "step 4: ask for the information, and store it into variables<br>\n",
    "step 5: check if the user types quit<br>\n",
    "step 5a: print out all information<br>\n",
    "step 5b: break out of the loop<br>\n",
    "step 6: if they didn't quit, add the information to the dictionary<br>\n",
    "step 7: invoke the function by calling it\n",
    "</p>"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 56,
   "metadata": {
    "scrolled": false
   },
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "What is your name and address?\n",
      "Enter quit to exit.\n",
      "Name: arpi\n",
      "Address: 179th st\n",
      "What is your name and address?\n",
      "Enter quit to exit.\n",
      "Name: ani\n",
      "Address: 179th st\n",
      "What is your name and address?\n",
      "Enter quit to exit.\n",
      "Name: quit\n",
      "arpi 179th st\n",
      "ani 179th st\n"
     ]
    }
   ],
   "source": [
    "from IPython.display import clear_output\n",
    "\n",
    "def takeInfo(name, address):\n",
    "    user_info = {}\n",
    "    while True:\n",
    "        print('What is your name and address?')\n",
    "        print('Enter quit to exit.')\n",
    "        name = input('Name: ')\n",
    "        if name == 'quit':\n",
    "            break\n",
    "        address = input('Address: ')\n",
    "        if address == 'quit':\n",
    "            break\n",
    "        user_info[name] = address\n",
    "    for name,address in user_info.items():\n",
    "        print(name, address)\n",
    "takeInfo(name, address)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Set <br>\n",
    "<p>A Set is an unordered collection data type that is iterable (loop), mutable, and has no duplicate elements.<br>Major advantage is that it is highly optimized in checking if something is in the set, as opposed to checking if something is in a list.</p>"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Declaring"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 57,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{1, 4, 6}\n"
     ]
    }
   ],
   "source": [
    "# set() or {}\n",
    "# no order {3, 2, 1} outputs as {1, 2, 3}\n",
    "\n",
    "nums = {4,1,6,4}\n",
    "print(nums) "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### .add()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 58,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{56, 1, 4, 6}\n"
     ]
    }
   ],
   "source": [
    "# set.add()\n",
    "nums.add(56)\n",
    "print(nums)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### .remove()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 59,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{1, 4, 6}\n"
     ]
    }
   ],
   "source": [
    "# removes by value\n",
    "# set.remove()\n",
    "# nums.remove(56)\n",
    "nums.remove(56)\n",
    "print(nums)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### .union() "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 60,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{1, 2, 3, 4, 5, 6}\n",
      "{1, 2, 3, 4, 5, 6}\n"
     ]
    }
   ],
   "source": [
    "# Returns a union of two sets, can also use '|' or set.union(set)\n",
    "# joins all numbers, gets rid of duplicates\n",
    "s1= {1,2,3,4}\n",
    "s2 ={3,4,5,6}\n",
    "\n",
    "s3 = s1.union(s2)\n",
    "# OR\n",
    "s4 = s1 | s2\n",
    "\n",
    "print(s3)\n",
    "print(s4)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### .intersection()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 61,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{3, 4}\n",
      "{3, 4}\n"
     ]
    }
   ],
   "source": [
    "# Returns an intersection of two sets, can also use '&'\n",
    "# only takes similar elements from both sets\n",
    "\n",
    "s5 = s2 & s1\n",
    "# 0R\n",
    "s6 = s1.intersection(s2)\n",
    "\n",
    "print(s5)\n",
    "print(s6)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### .difference()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 62,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{5, 6}\n",
      "{1, 2}\n"
     ]
    }
   ],
   "source": [
    "# Returns a set containing all the elements of invoking set that are not in the second set, can also use '-'\n",
    "# only takes values from the first set that are not in the second set\n",
    "# order matters\n",
    "\n",
    "s7 = s2 - s1\n",
    "# OR\n",
    "s8 = s1.difference(s2)\n",
    "\n",
    "print(s7)\n",
    "print(s8)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### .clear()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 63,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "set()\n"
     ]
    }
   ],
   "source": [
    "# Empties the whole set\n",
    "# set.clear()\n",
    "s8.clear()\n",
    "\n",
    "print(s8)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Frozenset <br>\n",
    "<p>Frozen sets are immutable objects that only support methods and operators that produce a result without affecting the frozen set or sets to which they are applied.</p><br><b>Unique & Immutable</b>"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 66,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "frozenset({1, 2, 3, 4, 5, 6})\n"
     ]
    }
   ],
   "source": [
    "# frozenset({})\n",
    "my_frozen_set = frozenset(s3) # original set is not frozen \n",
    "print(my_frozen_set) "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Modules"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Importing Entire Modules"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 67,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "3.141592653589793\n",
      "3\n"
     ]
    }
   ],
   "source": [
    "# import or from 'xxx' import *\n",
    "# import math\n",
    "import math\n",
    "\n",
    "print(math.pi)\n",
    "print(math.floor(math.pi))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Importing Methods Only"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 68,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "3.141592653589793\n",
      "3\n"
     ]
    }
   ],
   "source": [
    "# from 'xxx' import 'xxx'\n",
    "# from math import floor\n",
    "\n",
    "from math import floor, pi\n",
    "\n",
    "print(pi)\n",
    "print(floor(pi))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Using the 'as' Keyword"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 69,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "3.141592653589793\n",
      "3\n"
     ]
    }
   ],
   "source": [
    "# from 'xxx' import 'xxx' as 'xxx' or import 'xxx' as 'xxx'\n",
    "# from math import floor as f\n",
    "\n",
    "from math import floor as f, pi as p\n",
    "print(p)\n",
    "print(f(p))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##### Creating a Module"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 70,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hello Mr/Ms Anderson...we've been waiting for you!\n",
      "None\n"
     ]
    }
   ],
   "source": [
    "from module  import printName\n",
    "\n",
    "print(printName('Anderson'))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Exercises"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 1) Build a Shopping Cart <br>\n",
    "<p><b>You can use either lists or dictionaries. The program should have the following capabilities:</b><br><br>\n",
    "1) Takes in input <br>\n",
    "2) Stores user input into a dictionary or list <br>\n",
    "3) The User can add or delete items <br>\n",
    "4) The User can see current shopping list <br>\n",
    "5) The program Loops until user 'quits' <br>\n",
    "6) Upon quiting the program, print out all items in the user's list <br>\n",
    "</p>"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 92,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['apple']"
      ]
     },
     "execution_count": 92,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "from IPython.display import clear_output\n",
    "\n",
    "# Ask the user four bits of input: Do you want to : Show/Add/Delete or Quit?\n",
    "def ask_user():\n",
    "    user_input = []\n",
    "    while True:\n",
    "        print('What would you like to do?')\n",
    "        answer = input('Show/Add/Delete or Quit? ')\n",
    "        clear_output()\n",
    "        if answer == 'Add':\n",
    "            item = input('Type in your item: ')\n",
    "            user_input.append(item)\n",
    "        elif answer == 'Show':\n",
    "            for value in user_input:\n",
    "                print(value)\n",
    "        elif answer == 'Delete':\n",
    "            delete = input('Type the item you want to delete: ')\n",
    "            user_input.remove(delete)\n",
    "        elif answer == 'Quit':\n",
    "            break\n",
    "    return user_input\n",
    "ask_user()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 2) Create a Module in VS Code and Import It into jupyter notebook <br>\n",
    "<p><b>Module should have the following capabilities:</b><br><br>\n",
    "1) Has a function to calculate the square footage of a house <br>\n",
    "    <b>Reminder of Formula: Length X Width == Area<br>\n",
    "        <hr>\n",
    "2) Has a function to calculate the circumference of a circle <br><br>\n",
    "<b>Program in Jupyter Notebook should take in user input and use imported functions to calculate a circle's circumference or a houses square footage</b>\n",
    "</p>"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 94,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "30\n",
      "18.84955592153876\n"
     ]
    }
   ],
   "source": [
    "from square_footage import area\n",
    "\n",
    "print(area(5,6))\n",
    "\n",
    "from square_footage import circumference\n",
    "\n",
    "print(circumference(3))"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
