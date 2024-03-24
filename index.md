# On the Edit file tab, add a #, followed by a space, before any content you like to make it an H1 Header. You can add more headers, using one to six # characters followed by a space
##### ![Image of Yaktocat] https://octodex.github.com/images/yaktocat.png
```{python}
(def binary_search(arr, x):
    low = 0
    high = len(arr) - 1
    mid = 0

    while low <= high:
        mid = (high + low) // 2

        # If x is greater, ignore left half
        if arr[mid] < x:
            low = mid + 1

        # If x is smaller, ignore right half
        elif arr[mid] > x:
            high = mid - 1

        # x is present at mid
        else:
            return mid

    # If we reach here, then the element was not present
    return -1

# Example usage:
# Must be a sorted list
sorted_list = [2, 3, 4, 10, 40]
target = 10

result = binary_search(sorted_list, target)

if result != -1:
    print(f"Element is present at index {result}")
else:
    print("Element is not present in list")
```
- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
