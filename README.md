def linearSearchProduct (productList, targetProduct):

indices = []

for index, product in enumerate(productList):

if product == targetProduct:
indices.append(index)

return indices

# Example usage:

I

products = ["shoes", "boot", "loafer", "shoes", "sandal",

"shoes"]

target = "shoes"

result linearSearchProduct (products, target)

Sprint(result)
