# Getting Started

## 1. Get Token ID

* Login into [https://portal.biznetgio.com](https://portal.biznetgio.com)
* In the sidebar select AI and ML, then Face Recognition
* Click Create New Face Recognition Service&#x20;
* Fill in Service Name and Select Package, then press next&#x20;
* Choose a payment method, then click order, and make payment&#x20;
* Click the service that has been created, on the service page there is Token ID information

## 2. Take a Peek in Topology of API

The following is a generic top-level view of the system. You are the client.

![Topology](.gitbook/assets/index.png)

* **Client** is the admin or the owner of several FaceGallery. The lient is your program (application) that is accessing our API. The client may have access to multiple FaceGallery.
* **FaceGallery** is a collection of users from a place or area. Think of it as a “database”.
* **User** is the person who uses the API for recognition. User will give their **face** (to be exact) in the database.

## 3. Create New Facegallery

FaceGallery is a collection of users, please refer to this [API ](apis/face-api.md#post-facegallery-create-facegallery)to make a new Facegallery.

## 4. Play with the API

Try to [enroll ](apis/face-api.md#post-facegallery-enroll-face)a user and then try [identification](apis/face-api.md#post-facegallery-identify-face) and [verification](apis/face-api.md#post-facegallery-verify-face).

## 5. Still in trouble?

Look at [the tutorial for hitting API with Postman](others/postman-setting.md) or the [contact ](others/contat-person.md)person in charge.

{% embed url="https://documenter.getpostman.com/view/16178629/UVsEVpHD" %}
Postman API
{% endembed %}
