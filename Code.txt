import matplotlib.pyplot as plt
import numpy as np

 # from 1799 to 1837 make 5 points.
x = np.linspace(1799, 1837, 5)

 # y-line chart
y = 1

 # 1 is a graph in this line
fig, ax = plt.subplot()

 # function y(x)
ax.plot(x, y1, color="black", label="черная линия")

 # signature on horizontal x-axis
ax.set_xlabel("x")

 # signature vertical y-axis
ax.set_ylabel("y")

 # show legend
ax.legend()

 # save to file 1.png
fig.savefig('1.png')

 # show a picture
plt.show()
