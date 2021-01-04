# Day 3
_12/18/2020_

## What i learned in coding school is...
how to code

## 1. What problems does the Observer Pattern seek to solve?
     If in case you want to update parts of a code in response to certain events, then it leads into a lot of push-pull in the code to keep it in sync. But by using Observer Pattern it can be resolved as it enables one to many data biding.
      
## 2. What are the three mechanisms of the observe pattern?
    1. The Subscribe Method: Used to add new events.
    subscribe(fn){
      this.observer.push(fn)
    }
    2. The Unsubscribe Method: Used to remove events.
    unsubscribe(fn){
      this.observe = this.observe.filter((subscriber)=> subscriber != fn)
    }
    3. The Broadcast Method: Used to call all events.
    broadcast(data){
      this.observe.forEach((subscriber)=> subscriber(data))
    }

## 3. Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
    The Observer pattern is a software design in which an object has observers and then it notifies these observers automatically of any data change.

    The proxy Pattern is used for wrapping an object with one or more objects because it needs to be managed in a certain way that can be simplified via proxy objects.