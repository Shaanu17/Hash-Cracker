import hashlib

def crack_hash(hash_to_crack, hash_type, wordlist):
    for password in wordlist:
        if hash_type == 'md5':
            hashed_password = hashlib.md5(password.encode()).hexdigest()
        elif hash_type == 'sha1':
            hashed_password = hashlib.sha1(password.encode()).hexdigest()
        elif hash_type == 'sha256':
            hashed_password = hashlib.sha256(password.encode()).hexdigest()
        else:
            print("Unsupported hash type.")
            return None
        
        if hashed_password == hash_to_crack:
            return password
    return None

# Example usage
hash_to_crack = '5d41402abc4b2a76b9719d911017c592'  # Hash for 'hello'
hash_type = 'md5'
wordlist = ['hello', 'world', 'password', '123456']  # Add more common passwords here

found_password = crack_hash(hash_to_crack, hash_type, wordlist)

if found_password:
    print(f"Password found: {found_password}")
else:
    print("Password not found.")
