# Caching

## What is Caching?
Caching is like having a secret storage place for things you use a lot so you don't have to go get them from far away every time. It's like keeping your favorite snacks in a drawer at your desk instead of going to the kitchen each time you want a snack.

## How does caching work?
Caching is like having a quick-access storage for things you use often. Here's how it works:
1. **Request for Data:** 
   * When you request data from the system it first checks if it is already in the cache or not. It's like if you need something then check it first in your nearest closet.
2. **Cache Check:** 
   * If the data is in the cache it will be delivered to you. It is like finding your favorite book on a shelf right next to you.
   * If the data is not in the cache then the system goes for the other external resources and then it will be delivered to you. 
3. **Data Storage in Cache:** 
   * After fetching the data from the source, the system stores a copy of it in the cache. so that if you need that data in the future it will quickly delivered to you.
4. **Cache Expiry and Invalidation:**
   * Cached data is not kept forever. It has an expiration date. When the data becomes outdated it needs to be replaced with fresh data from the source. This is called cache expiration.
   * Cache invalidation is a process that removes outdated or irrelevant data from the cache ensuring that you always get the latest and correct information.
5. **Faster Access:**
   * The next time you or someone else requests the same data, the system can deliver it from the cache which is much faster than getting it from an external source. It's like having a saved copy of your favorite video ready to play instantly.
 
 
## Different approaches to caching
The steps you need to follow are:

* **Understand the Problems:** Firstly try to find out what is making the project slow and why it is getting so big. 
* **Choose What to store:** Decide what parts of the project can be stored in a quick-access place, like storing your favorite toys that you use a lot on a shelf instead of in a toy box.
* **Pick the Right Tools:** There are different ways to do this like using tools that are being used for this.
* **Decide How Long Data Get Stored:** Just like snacks can get old, cached data can too. You need to decide how long the stored information is good for so that after some time it can be replaced with the new one.
* **Start Using Caching:** Put the frequently used information in this special storage so you can get it faster when needed.
* **Keep an Eye on It:** Make sure the special storage is working well and making things faster. If not then you might need to adjust it.
* **Test It First:** Before using it in the actual project test it to make sure it works without causing any problems.
* **Use It in the Project:** Once you are sure it's working start using it in the project to make things faster.
* **Check It Regularly:** Keep an eye on it to make sure it's still doing its job. If the project changes, you might need to change the way you are using this special storage.
* **Teach Your Team:** Make sure your team members know how to use this special storage to make the project better.
     
By using caching you can make the project work faster and solve the problems it's facing. It's like having your favorite snacks right on your desk to enjoy quickly.


## References:
1. [Amazon Web Services](https://aws.amazon.com/caching/)
2. [Geeksforgeeks](https://www.geeksforgeeks.org/system-design-horizontal-and-vertical-scaling/)
3. [Amazon Web Services](https://docs.aws.amazon.com/whitepapers/latest/database-caching-strategies-using-redis/caching-patterns.html)
4. [Medium](https://medium.com/@mmoshikoo/cache-strategies-996e91c80303)
