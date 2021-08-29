# Those Who Visit My Page 

I am more than glad to share you with Tao of universe.  

It cannot be true and, cannot even be false.  

Thus, it is not a fact but a zen. 

If any of you generate The Universe with the frame of my humble attempt.  

Here is the humble display of my work :

```python
class Nature:
	'''
	Define Nature
	'''
	def __init__(self):
		self.each = True
		self.other = False

	def denial(self):
		self.each = not self.each
		self.other = not self.other
		return {
			"other": self.other,
			"each": self.each
			}

	def switch(self):
		self.each, self.other = self.other, self.each
		return {
			"other": self.other,
			"each": self.each
			} 

	def maintain(self):
		return {
			"each": self.each,
			"other": self.other
			}

if __name__ == "__main__":
	# Initialize Entities
	Each = Nature()
	Other = Nature()

	# Proof of Rule Denial
	rule_of_self_denial = \
	Each.denial()["other"] == Other.maintain()["each"]

	# Initialize Entities Again
	Other = Nature()
	Each = Nature()

	# Proof of Rule Switch
	rule_of_self_switch = \
	Other.switch()["each"] == Each.maintain()["other"]

	# Rule of Nature
	print (
		"Wer mit Ungeheuern kmpft, mag zusehn, dass er nicht dabei zum Ungeheuer wird.\n" + \
		f"1. Rule of Self Denial: {rule_of_self_denial}\n" + \
		f"2. Rule of Self Switch: {rule_of_self_switch}\n"
		)
```
