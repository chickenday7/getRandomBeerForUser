<template>
  <div class="wrapperApp">
    <UserName/>
    <AboutUser/>
    <Contacts/>
    <Tittle/>
    <Avatar/>
    <BearBtn/>
    <NextUser/>
    <Employment title="Employment"/>
    <Payment/>
    <Subscription/>
    <AddressUser/>
  </div>
</template>

<script>
import UserName from "./Username/UserName";
import AboutUser from "./AboutUser/AboutUser";
import Contacts from "./Contacts/Contacts";
import Tittle from "./Tittle/Tittle";
import Avatar from "./Avatar/Avatar";
import BearBtn from "./BeerBtn/BeerBtn";
import NextUser from "./NextUser/NextUser";
import Employment from "./Employment/Employment";
import Payment from "./Payment/Payment";
import Subscription from "./Subscription/Subscription";
import AddressUser from "./AddressUser/AddressUser";
import('./smartGangAppStyle.scss')
export default {
  name: "SmartGangApp",
  components: {
    AddressUser,
    Subscription, Payment, Employment, NextUser, BearBtn, Avatar, Tittle, Contacts, AboutUser, UserName}
}
</script>

<style scoped>

</style>
