Download Link: https://assignmentchef.com/product/solved-adipvc-assignment3-paintings-of-picasso-and-bezille
<br>
Consider images of paintings of Picasso and Bezille (provided in two zip files). Write programs for the following.

For each data set perform the following operations.

(i) Randomly sample N patches of size mxmx3. Typical values of N and

m are  1000, and 8, respectively,

<ul>

 <li>Create an over-complete set of dictionary for each of them separately using K-SVD algorithm for sparse representation. Typical value of K is 256.</li>

 <li>Derive a sparse representation with q atoms of all the images for each data set using their respective dictionaries.Typical value of q is 5. Use 4-byte floating point representation for the coefficients. Implement also reconstruction of images from their sparse representation. Find the compression ratio of the representation and also the PSNR of the reconstructed images w.r.t. original images.</li>

 <li>Compute minimum cost bipartite matching of two dictionaries, where cost between two atoms of each dictionary is defined by the L2 norm of their differences.</li>

 <li>Transform the paintings of one artist to the other by replacing an atom with its matched partner (as computed in (iv)) and display those images and PSNR values.</li>

</ul>

Marking Policy:

<ul>

 <li>Random sampling to generate data points for dictionary</li>

</ul>

building.: 10

<ul>

 <li>Implementation of K-SVD algorithm. You may use library</li>

</ul>

function.: 15

<ul>

 <li>Deriving sparse representation and reconstructing images from it: 20</li>

 <li>Computation and results of compression ratio and PSNR for each images for each data set (to be provided as Tables in the report). :</li>

</ul>

15

<ul>

 <li>Minimum cost bipartite matching: 20.</li>

 <li>Transformation of paintings and reporting of results: 10</li>

 <li>Report: 10</li>

</ul>

Bonus: Quality of solution (10)

You may implement your programs in  C++-OpenCV/MATLAB/ Python  with necessary user’s interfaces and visualization of your results and input.

Please provide a documentation for compiling and running the programs in a README file. The whole project should be submitted in a single tar or zip file.