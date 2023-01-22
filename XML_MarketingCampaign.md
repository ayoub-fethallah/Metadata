<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.xml.xsd" id="_Z_gvA4rqEeqdU-y7qvz1lw" name="marketingCampaign.xml" md:ref="platform:/plugin/com.indy.environment/technology/file/default.xml.md#UUID_MD_XML_DEFAULT?fileId=UUID_MD_XML_DEFAULT$type=md$name=Xml?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.xml.xsd.xsdReverseVersion" id="_Z_gvBIrqEeqdU-y7qvz1lw" value="1"/>
  <attribute defType="com.stambia.xml.xsd.xmlPath" id="_Z_gvBYrqEeqdU-y7qvz1lw" value="%{env:workspace_loc}%\Training\Files_In\Xml\marketingCampaign.xml"/>
  <attribute defType="com.stambia.xml.xsd.xsdPath" id="_Z_gvBorqEeqdU-y7qvz1lw" value="%{env:workspace_loc}%\Training\Files_In\Xml\hotelManagement.xsd"/>
  <attribute defType="com.stambia.xml.xsd.prefixForElement" id="_Z_gvB4rqEeqdU-y7qvz1lw" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.prefixForAttribute" id="_Z_gvCIrqEeqdU-y7qvz1lw" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.targetNamespace" id="_Z_gvCYrqEeqdU-y7qvz1lw" value="http://stambia.org/samples/management"/>
  <node defType="com.stambia.xml.namespace" id="_Z_gvCorqEeqdU-y7qvz1lw" name="http://stambia.org/samples/common">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_gvC4rqEeqdU-y7qvz1lw" value="com"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_gvDIrqEeqdU-y7qvz1lw" name="http://stambia.org/samples/management">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_gvDYrqEeqdU-y7qvz1lw" value="mgt"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_gvDorqEeqdU-y7qvz1lw" name="http://www.w3.org/2001/XMLSchema">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_gvD4rqEeqdU-y7qvz1lw" value="xs"/>
  </node>
  <node defType="com.stambia.xml.root" id="_Z_gvEIrqEeqdU-y7qvz1lw" name="marketingCampaign" position="0">
    <node defType="com.stambia.xml.sequence" id="_Z_gvEYrqEeqdU-y7qvz1lw" position="3">
      <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_gvEorqEeqdU-y7qvz1lw" value="1"/>
      <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_gvE4rqEeqdU-y7qvz1lw" value="1"/>
      <node defType="com.stambia.xml.element" id="_Z_gvFIrqEeqdU-y7qvz1lw" name="phoningCampaign" position="0">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_gvFYrqEeqdU-y7qvz1lw" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_gvForqEeqdU-y7qvz1lw" value="1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_Z_gvF4rqEeqdU-y7qvz1lw" value="mgt:PhoningCampaign"/>
        <node defType="com.stambia.xml.attribute" id="_Z_gvGIrqEeqdU-y7qvz1lw" name="campaignId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvGYrqEeqdU-y7qvz1lw" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvGorqEeqdU-y7qvz1lw" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvG4rqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_gvHIrqEeqdU-y7qvz1lw" name="name" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvHYrqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvHorqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvH4rqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_gvIIrqEeqdU-y7qvz1lw" name="startDate" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvIYrqEeqdU-y7qvz1lw" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvIorqEeqdU-y7qvz1lw" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvI4rqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_gvJIrqEeqdU-y7qvz1lw" name="endDate" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvJYrqEeqdU-y7qvz1lw" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvJorqEeqdU-y7qvz1lw" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvJ4rqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_Z_gvKIrqEeqdU-y7qvz1lw" position="7">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_gvKYrqEeqdU-y7qvz1lw" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_gvKorqEeqdU-y7qvz1lw" value="1"/>
          <node defType="com.stambia.xml.element" id="_Z_gvK4rqEeqdU-y7qvz1lw" name="customer" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_gvLIrqEeqdU-y7qvz1lw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_gvLYrqEeqdU-y7qvz1lw" value="-1"/>
            <attribute defType="com.stambia.xml.element.alternateName" id="_Z_gvLorqEeqdU-y7qvz1lw" value="phoneCustomer"/>
            <node defType="com.stambia.xml.attribute" id="_Z_gvL4rqEeqdU-y7qvz1lw" name="customerId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvMIrqEeqdU-y7qvz1lw" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvMYrqEeqdU-y7qvz1lw" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvMorqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvM4rqEeqdU-y7qvz1lw" name="titleCode" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvNIrqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvNYrqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvNorqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvN4rqEeqdU-y7qvz1lw" name="title" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvOIrqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvOYrqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvOorqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvO4rqEeqdU-y7qvz1lw" name="firstName" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvPIrqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvPYrqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvPorqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvP4rqEeqdU-y7qvz1lw" name="lastName" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvQIrqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvQYrqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvQorqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvQ4rqEeqdU-y7qvz1lw" name="company" position="5">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvRIrqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvRYrqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvRorqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvR4rqEeqdU-y7qvz1lw" name="birthDate" position="6">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvSIrqEeqdU-y7qvz1lw" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvSYrqEeqdU-y7qvz1lw" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvSorqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.sequence" id="_Z_gvS4rqEeqdU-y7qvz1lw" position="10">
              <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_gvTIrqEeqdU-y7qvz1lw" value="1"/>
              <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_gvTYrqEeqdU-y7qvz1lw" value="1"/>
              <node defType="com.stambia.xml.element" id="_Z_gvTorqEeqdU-y7qvz1lw" name="phone" position="0">
                <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_gvT4rqEeqdU-y7qvz1lw" value="0"/>
                <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_gvUIrqEeqdU-y7qvz1lw" value="-1"/>
                <attribute defType="com.stambia.xml.element.originalType" id="_Z_gvUYrqEeqdU-y7qvz1lw" value="com:Phone"/>
                <node defType="com.stambia.xml.attribute" id="_Z_gvUorqEeqdU-y7qvz1lw" name="phoneId" position="0">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvU4rqEeqdU-y7qvz1lw" value="integer"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvVIrqEeqdU-y7qvz1lw" value="xs:integer"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvVYrqEeqdU-y7qvz1lw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Z_gvVorqEeqdU-y7qvz1lw" name="phoneTypeCode" position="1">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvV4rqEeqdU-y7qvz1lw" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvWIrqEeqdU-y7qvz1lw" value="xs:string"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvWYrqEeqdU-y7qvz1lw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Z_gvWorqEeqdU-y7qvz1lw" name="phoneNumber" position="2">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvW4rqEeqdU-y7qvz1lw" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvXIrqEeqdU-y7qvz1lw" value="xs:string"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvXYrqEeqdU-y7qvz1lw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Z_gvXorqEeqdU-y7qvz1lw" name="phoneType" position="3">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvX4rqEeqdU-y7qvz1lw" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvYIrqEeqdU-y7qvz1lw" value="xs:string"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvYYrqEeqdU-y7qvz1lw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Z_gvYorqEeqdU-y7qvz1lw" name="phoningAllowed" position="4">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvY4rqEeqdU-y7qvz1lw" value="boolean"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvZIrqEeqdU-y7qvz1lw" value="xs:boolean"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvZYrqEeqdU-y7qvz1lw" value="optional"/>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
      <node defType="com.stambia.xml.element" id="_Z_gvZorqEeqdU-y7qvz1lw" name="mailingCampaign" position="1">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_gvZ4rqEeqdU-y7qvz1lw" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_gvaIrqEeqdU-y7qvz1lw" value="1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_Z_gvaYrqEeqdU-y7qvz1lw" value="mgt:MailingCampaign"/>
        <node defType="com.stambia.xml.attribute" id="_Z_gvaorqEeqdU-y7qvz1lw" name="campaignId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gva4rqEeqdU-y7qvz1lw" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvbIrqEeqdU-y7qvz1lw" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvbYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_gvborqEeqdU-y7qvz1lw" name="name" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvb4rqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvcIrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvcYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_gvcorqEeqdU-y7qvz1lw" name="startDate" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvc4rqEeqdU-y7qvz1lw" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvdIrqEeqdU-y7qvz1lw" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvdYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_gvdorqEeqdU-y7qvz1lw" name="endDate" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvd4rqEeqdU-y7qvz1lw" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gveIrqEeqdU-y7qvz1lw" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gveYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_Z_gveorqEeqdU-y7qvz1lw" position="7">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_gve4rqEeqdU-y7qvz1lw" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_gvfIrqEeqdU-y7qvz1lw" value="1"/>
          <node defType="com.stambia.xml.element" id="_Z_gvfYrqEeqdU-y7qvz1lw" name="customer" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_gvforqEeqdU-y7qvz1lw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_gvf4rqEeqdU-y7qvz1lw" value="-1"/>
            <attribute defType="com.stambia.xml.element.alternateName" id="_Z_gvgIrqEeqdU-y7qvz1lw" value="mailCustomer"/>
            <node defType="com.stambia.xml.attribute" id="_Z_gvgYrqEeqdU-y7qvz1lw" name="customerId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvgorqEeqdU-y7qvz1lw" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvg4rqEeqdU-y7qvz1lw" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvhIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvhYrqEeqdU-y7qvz1lw" name="titleCode" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvhorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvh4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gviIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gviYrqEeqdU-y7qvz1lw" name="title" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gviorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvi4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvjIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvjYrqEeqdU-y7qvz1lw" name="firstName" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvjorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvj4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvkIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvkYrqEeqdU-y7qvz1lw" name="lastName" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvkorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvk4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvlIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvlYrqEeqdU-y7qvz1lw" name="company" position="5">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvlorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvl4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvmIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gvmYrqEeqdU-y7qvz1lw" name="birthDate" position="6">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvmorqEeqdU-y7qvz1lw" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvm4rqEeqdU-y7qvz1lw" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvnIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.sequence" id="_Z_gvnYrqEeqdU-y7qvz1lw" position="10">
              <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_gvnorqEeqdU-y7qvz1lw" value="1"/>
              <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_gvn4rqEeqdU-y7qvz1lw" value="1"/>
              <node defType="com.stambia.xml.element" id="_Z_gvoIrqEeqdU-y7qvz1lw" name="email" position="0">
                <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_gvoYrqEeqdU-y7qvz1lw" value="0"/>
                <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_gvoorqEeqdU-y7qvz1lw" value="-1"/>
                <attribute defType="com.stambia.xml.element.originalType" id="_Z_gvo4rqEeqdU-y7qvz1lw" value="com:Email"/>
                <node defType="com.stambia.xml.attribute" id="_Z_gvpIrqEeqdU-y7qvz1lw" name="emailId" position="0">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvpYrqEeqdU-y7qvz1lw" value="integer"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvporqEeqdU-y7qvz1lw" value="xs:integer"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvp4rqEeqdU-y7qvz1lw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Z_gvqIrqEeqdU-y7qvz1lw" name="emailAddress" position="1">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvqYrqEeqdU-y7qvz1lw" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvqorqEeqdU-y7qvz1lw" value="xs:string"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvq4rqEeqdU-y7qvz1lw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Z_gvrIrqEeqdU-y7qvz1lw" name="emailType" position="2">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvrYrqEeqdU-y7qvz1lw" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvrorqEeqdU-y7qvz1lw" value="xs:string"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvr4rqEeqdU-y7qvz1lw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Z_gvsIrqEeqdU-y7qvz1lw" name="mailingAllowed" position="3">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvsYrqEeqdU-y7qvz1lw" value="boolean"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvsorqEeqdU-y7qvz1lw" value="xs:boolean"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvs4rqEeqdU-y7qvz1lw" value="optional"/>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>