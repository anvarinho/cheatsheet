# Shell Commands

```sh
# echo "What is your name?"
# read name
user=$(whoami)
date=$(date)
dir=$(pwd)
name=$1
comp=$2
echo "Hello $user!"
sleep 1
echo "You are looking great $name, now is $date!!!!!"
sleep 1
echo "$1, you have a best $comp I've ever seen. You are in $dir directory"
```

## Open browser

```sh

open -a safari https://www.youtube.com/results?search_query=music

```

### Other commands

```sh

# echo "What is your name?"

# read name

# echo "How old are you?"

# read age

# echo "Hello $name, you are $age years old!!!!!"

# echo "$USER $RANDOM $PWD $SHELL $HOSTNAME"

echo "You died"

# echo "Do you wanna get alive? (y/n)"

# read ans

# if [[$ans == "y"]]; then

# echo "Awesome"

# else

# echo "Leave right now"

# fi

math=$(($RANDOM % 2))
echo "1 or 0 choose one"
read val

if [[$math == $val]]; then
echo "You are lucky"
else
echo "You died"
fi

```
