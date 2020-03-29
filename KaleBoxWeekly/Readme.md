# Web-Stack-Project
Web Stack Project
Project Proposal
Kale Subscription Box

Short Description:
This service will be a monthly subscription box for purchasing Kale in an assortment of boxes with differing designs. You always get kale, but the options for boxes change with your taste. 

Github: https://github.com/elalden/Web-Stack-Project

Preliminary Data Model:
    Custom User Model
    Username
    Password
    Email
    Cart(FK)
    Address
    Card Info
Shopping Cart:
    Item(s)
    UserID(FK -> username)
    Price
    Subscription(FK->subscription type)
Box:
    Name(PK)
    Price
    Subscription
    Type(one time, monthly, weekly)(pk)
    Discount

Preliminary Functional Areas:
    .Users can register for the website with email, username, password, and their address info
    .Users shop through a catalog of boxes with different filters for price, type, and availability. 
    .Users can choose multiple boxes and can choose the order in which to receive them if they are using a subscription. 
    .Users may choose one type of box and receive it for the duration 
    .Users can choose either a one time, weekly, or monthly subscription
    .Weekly and monthly subscriptions can be cancelled
    .Users boxes are then sent to their shopping cart where their choices will be saved until they checkout
    .Users choose the order of boxes in their subscription as well as the subscription duration here
    .Users are able to up or lower the quantity of selected items
    .The shopping cart will have  a ‘Clear cart’ option, and each option can be removed individually in case 
