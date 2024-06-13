In this project of Creating a Token  Firstly I have created a Contract Which will Store the details
of Mytoken which are Tname , Tabbvr , and Final Supply .I have made these variables public so that anyone 
can access them

In second Step I have created a mapping Variable to track how many tokens each address holds .
the keys of the mapping are etherium addresses .the values are unsigned integers as they cannot be negative
which are representing the token balance associated with each address.

In Third step I have created a Mint function that allows new tokens to be addedto the assigned address
.and  Parameters which i have used are _address and _ num. Increases the finalsupply by the _num and Increses 
the balance of the _address by the _num . All can access it so i had made it public.

The fourth step is to create a burn function. This function will destroy a specified number of tokens from a given address,
which is the opposite of the mint function. It will check if the address has enough tokens to burn. If it does, the function
will reduce both the total supply of tokens and the balance of the address by that amount. This check ensures that tokens are
not burned accidentally or in excess.
