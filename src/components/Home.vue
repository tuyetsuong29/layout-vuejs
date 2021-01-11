<template>
  <body-wrapper>
    <sidebar-wrapper>
      <name-link>
        <p>Home</p>
        <p>Home</p>
        <p>Home</p>
        <p>Home</p>
        <p>Home</p>
      </name-link>
    </sidebar-wrapper>
    <container>
      <header-wrraper>Home.something</header-wrraper>
      <body-wrraper>
        <card-body>write something here...</card-body>
      </body-wrraper>
    </container>
  </body-wrapper>
</template>
<script>
import {
  BodyWrapper,
  Container,
  BodyWrraper,
  HeaderWrraper,
  SidebarWrapper,
  NameLink,
  CardBody,
} from "./styled";

export default {
  components: {
    BodyWrapper,
    Container,
    HeaderWrraper,
    BodyWrraper,
    SidebarWrapper,
    NameLink,
    CardBody,
  },
};
</script>
