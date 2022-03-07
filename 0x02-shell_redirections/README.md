Shell, I/O Redirections and Filters

echo "Hello, World" ===  prints “Hello, World”, followed by a new line to the standard output

echo "\"(Ôo)'" === displays a confused smiley

cat /etc/passwd ===  display the content of /etc/passwd

cat /etc/passwd /etc/hosts === Display the content of /etc/passwd and /etc/hosts

tail -n 10 /etc/passwd === Display the last 10 lines of /etc/passwd

head -n 10 /etc/passwd === Display the first 10 lines of /etc/passwd

head -n 3 iacta | tail -n 1 === displays the third line of the file iacta.

echo "Best School" | cat > '\*\\'\''"Best School"\'\''\\*$\?\*\*\*\*\*:)' ===  creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

ls -la > ls_cwd_content === writes into the file ls_cwd_content the result of the command ls -la.



