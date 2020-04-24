---


---

<h1 id="assignment3-quarter3">Assignment3 Quarter3</h1>
<h2 id="multitasking">Multitasking:</h2>
<p>Multitasking is when a CPU is provided to execute <strong>multiple tasks</strong> at a time.<br>
Multitasking involves often CPU switching between the tasks, so that users can collaborate with each program together. Unlike <strong>multithreading</strong>, In <strong>multitasking</strong>, the processes share separate memory and resources. As multitasking involves CPU switching between the tasks rapidly, So the little time is needed in order to switch from the one user to next.</p>
<p>One of the fundamental features of most operating systems is multitasking, which is the ability to execute multiple tasks concurrently. For example, you probably have other programs open while looking at this post, such as a text editor or a terminal window. Even if you have only a single browser window open, there are probably various background tasks for managing your desktop windows, checking for updates, or indexing files.</p>
<blockquote>
<p>There are two forms of multitasking: Cooperative multitasking requires tasks to regularly give up control of the CPU so that other tasks can make progress. Preemptive multitasking uses operating system functionality to switch threads at arbitrary points in time by forcibly pausing them. In the following we will explore the two forms of multitasking in more detail and discuss their respective advantages and drawbacks.</p>
</blockquote>
<p>While it seems like all tasks run in parallel, only a single task can be executed on a CPU core at a time. To create the illusion that the tasks run in parallel, the operating system rapidly switches between active tasks so that each one can make a bit of progress. Since computers are fast, we don’t notice these switches most of the time.<br>
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20191229191005/Untitled-Diagram-227.png" alt="enter image description here"></p>
<h2 id="multithreading">Multithreading:</h2>
<p>Multithreading is a system in which many threads are created from a process through which the computational power is increased. In multithreading, CPU is provided in order to execute many threads from a process at a time, and in multithreading, process creation is performed according to cost. Unlike multitasking, multithreading provides the same memory and resources to the processes for execution.<br>
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20191229182041/Untitled-Diagram-3511.png" alt="enter image description here"></p>
<h2 id="multitasking-vs-multithreading">Multitasking v/s Multithreading</h2>
<p><strong>Let’s see the difference between multitasking and multithreading:</strong></p>

<table>
<thead>
<tr>
<th>S . No</th>
<th>Multitasking</th>
<th>Multithreading</th>
</tr>
</thead>
<tbody>
<tr>
<td>1</td>
<td>In multitasking, users are allowed to perform many tasks by CPU.</td>
<td>While in multithreading, many threads are created from a process through which computer power is increased.</td>
</tr>
<tr>
<td>2</td>
<td>Multitasking involves often CPU switching between the tasks.</td>
<td>While in multithreading also, CPU switching is often involved between the threads.</td>
</tr>
<tr>
<td>3</td>
<td>In multitasking, the processes share separate memory.</td>
<td>While in multithreading, processes are allocated same memory.</td>
</tr>
<tr>
<td>4</td>
<td>Multitasking component involves multiprocessing.</td>
<td>While multithreading component does not involve multiprocessing.</td>
</tr>
<tr>
<td>5</td>
<td>In multitasking, CPU is provided in order to execute many tasks at a time.</td>
<td>While in multithreading also, CPU is provided in order to execute many threads from a process at a time.</td>
</tr>
<tr>
<td>6</td>
<td>In multitasking, processes don’t share same resources, each process is allocated separate resources.</td>
<td>While in multithreading, each process share same resources.</td>
</tr>
</tbody>
</table>
