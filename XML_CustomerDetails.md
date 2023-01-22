<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.xml.xsd" id="_Z_fhVYrqEeqdU-y7qvz1lw" name="hotelManagement.xsd" md:ref="platform:/plugin/com.indy.environment/technology/file/default.xml.md#UUID_MD_XML_DEFAULT?fileId=UUID_MD_XML_DEFAULT$type=md$name=Xml?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.xml.xsd.xsdReverseVersion" id="_Z_fhVorqEeqdU-y7qvz1lw" value="1"/>
  <attribute defType="com.stambia.xml.xsd.xsdPath" id="_Z_fhV4rqEeqdU-y7qvz1lw" value="%{env:workspace_loc}%\Training\Files_In\Xml\hotelManagement.xsd"/>
  <attribute defType="com.stambia.xml.xsd.prefixForElement" id="_Z_fhWIrqEeqdU-y7qvz1lw" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.prefixForAttribute" id="_Z_fhWYrqEeqdU-y7qvz1lw" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.targetNamespace" id="_Z_fhWorqEeqdU-y7qvz1lw" value="http://stambia.org/samples/management"/>
  <attribute defType="com.stambia.xml.xsd.xmlPath" id="_Z_fhW4rqEeqdU-y7qvz1lw" value="%{env:workspace_loc}%\Training\Files_Out\Xml\customerDetails.xml"/>
  <node defType="com.stambia.xml.namespace" id="_Z_fhXIrqEeqdU-y7qvz1lw" name="http://stambia.org/samples/common">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fhXYrqEeqdU-y7qvz1lw" value="com"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_fhXorqEeqdU-y7qvz1lw" name="http://stambia.org/samples/management">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fhX4rqEeqdU-y7qvz1lw" value="mgt"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_fhYIrqEeqdU-y7qvz1lw" name="http://www.w3.org/2001/XMLSchema">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fhYYrqEeqdU-y7qvz1lw" value="xs"/>
  </node>
  <node defType="com.stambia.xml.root" id="_Z_fhYorqEeqdU-y7qvz1lw" name="hotelManagement" position="0">
    <node defType="com.stambia.xml.sequence" id="_Z_fhY4rqEeqdU-y7qvz1lw" position="3">
      <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_fhZIrqEeqdU-y7qvz1lw" value="1"/>
      <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_fhZYrqEeqdU-y7qvz1lw" value="1"/>
      <node defType="com.stambia.xml.element" id="_Z_fhZorqEeqdU-y7qvz1lw" name="customer" position="0">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhZ4rqEeqdU-y7qvz1lw" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhaIrqEeqdU-y7qvz1lw" value="-1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhaYrqEeqdU-y7qvz1lw" value="mgt:CustomerDetail"/>
        <node defType="com.stambia.xml.attribute" id="_Z_fhaorqEeqdU-y7qvz1lw" name="customerId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fha4rqEeqdU-y7qvz1lw" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhbIrqEeqdU-y7qvz1lw" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhbYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fhborqEeqdU-y7qvz1lw" name="titleCode" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhb4rqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhcIrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhcYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fhcorqEeqdU-y7qvz1lw" name="title" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhc4rqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhdIrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhdYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fhdorqEeqdU-y7qvz1lw" name="firstName" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhd4rqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fheIrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fheYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fheorqEeqdU-y7qvz1lw" name="lastName" position="4">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhe4rqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhfIrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhfYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fhforqEeqdU-y7qvz1lw" name="company" position="5">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhf4rqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhgIrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhgYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fhgorqEeqdU-y7qvz1lw" name="birthDate" position="6">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhg4rqEeqdU-y7qvz1lw" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhhIrqEeqdU-y7qvz1lw" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhhYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_Z_fhhorqEeqdU-y7qvz1lw" position="10">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_fhh4rqEeqdU-y7qvz1lw" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_fhiIrqEeqdU-y7qvz1lw" value="1"/>
          <node defType="com.stambia.xml.element" id="_Z_fhiYrqEeqdU-y7qvz1lw" name="address" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhiorqEeqdU-y7qvz1lw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhi4rqEeqdU-y7qvz1lw" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhjIrqEeqdU-y7qvz1lw" value="com:Address"/>
            <node defType="com.stambia.xml.attribute" id="_Z_fhjYrqEeqdU-y7qvz1lw" name="addressId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhjorqEeqdU-y7qvz1lw" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhj4rqEeqdU-y7qvz1lw" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhkIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhkYrqEeqdU-y7qvz1lw" name="line1" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhkorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhk4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhlIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhlYrqEeqdU-y7qvz1lw" name="line2" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhlorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhl4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhmIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhmYrqEeqdU-y7qvz1lw" name="line3" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhmorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhm4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhnIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhnYrqEeqdU-y7qvz1lw" name="line4" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhnorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhn4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhoIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhoYrqEeqdU-y7qvz1lw" name="zipCode" position="5">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhoorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fho4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhpIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhpYrqEeqdU-y7qvz1lw" name="city" position="6">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhporqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhp4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhqIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhqYrqEeqdU-y7qvz1lw" name="stateCode" position="7">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhqorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhq4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhrIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="_Z_fhrYrqEeqdU-y7qvz1lw" name="phone" position="1">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhrorqEeqdU-y7qvz1lw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhr4rqEeqdU-y7qvz1lw" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhsIrqEeqdU-y7qvz1lw" value="com:Phone"/>
            <node defType="com.stambia.xml.attribute" id="_Z_fhsYrqEeqdU-y7qvz1lw" name="phoneId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhsorqEeqdU-y7qvz1lw" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhs4rqEeqdU-y7qvz1lw" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhtIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhtYrqEeqdU-y7qvz1lw" name="phoneTypeCode" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhtorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fht4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhuIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhuYrqEeqdU-y7qvz1lw" name="phoneNumber" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhuorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhu4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhvIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhvYrqEeqdU-y7qvz1lw" name="phoneType" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhvorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhv4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhwIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhwYrqEeqdU-y7qvz1lw" name="phoningAllowed" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhworqEeqdU-y7qvz1lw" value="boolean"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhw4rqEeqdU-y7qvz1lw" value="xs:boolean"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhxIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="_Z_fhxYrqEeqdU-y7qvz1lw" name="email" position="2">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhxorqEeqdU-y7qvz1lw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhx4rqEeqdU-y7qvz1lw" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhyIrqEeqdU-y7qvz1lw" value="com:Email"/>
            <node defType="com.stambia.xml.attribute" id="_Z_fhyYrqEeqdU-y7qvz1lw" name="emailId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhyorqEeqdU-y7qvz1lw" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhy4rqEeqdU-y7qvz1lw" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fhzIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fhzYrqEeqdU-y7qvz1lw" name="emailAddress" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fhzorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fhz4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fh0IrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fh0YrqEeqdU-y7qvz1lw" name="emailType" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fh0orqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fh04rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fh1IrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fh1YrqEeqdU-y7qvz1lw" name="mailingAllowed" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fh1orqEeqdU-y7qvz1lw" value="boolean"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fh14rqEeqdU-y7qvz1lw" value="xs:boolean"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fh2IrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="_Z_fh2YrqEeqdU-y7qvz1lw" name="bill" position="3">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fh2orqEeqdU-y7qvz1lw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fh24rqEeqdU-y7qvz1lw" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_Z_fh3IrqEeqdU-y7qvz1lw" value="com:Bill"/>
            <node defType="com.stambia.xml.attribute" id="_Z_fh3YrqEeqdU-y7qvz1lw" name="billId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fh3orqEeqdU-y7qvz1lw" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fh34rqEeqdU-y7qvz1lw" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fh4IrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fh4YrqEeqdU-y7qvz1lw" name="billDate" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fh4orqEeqdU-y7qvz1lw" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fh44rqEeqdU-y7qvz1lw" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fh5IrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fh5YrqEeqdU-y7qvz1lw" name="paymentTypeCode" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fh5orqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fh54rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fh6IrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fh6YrqEeqdU-y7qvz1lw" name="paymentType" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fh6orqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fh64rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fh7IrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fh7YrqEeqdU-y7qvz1lw" name="paymentDate" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fh7orqEeqdU-y7qvz1lw" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fh74rqEeqdU-y7qvz1lw" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fh8IrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_fh8YrqEeqdU-y7qvz1lw" name="totalAmount" position="5">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_fh8orqEeqdU-y7qvz1lw" value="decimal"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fh84rqEeqdU-y7qvz1lw" value="xs:decimal"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_fh9IrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
          </node>
        </node>
        <node defType="com.stambia.xml.propertyField" id="_Z_fh9YrqEeqdU-y7qvz1lw" name="sortLastname">
          <attribute defType="com.stambia.xml.propertyField.property" id="_Z_fh9orqEeqdU-y7qvz1lw" value="sortKey"/>
        </node>
        <node defType="com.stambia.xml.propertyField" id="_Z_fh94rqEeqdU-y7qvz1lw" name="SortFirstname">
          <attribute defType="com.stambia.xml.propertyField.property" id="_Z_fh-IrqEeqdU-y7qvz1lw" value="sortKey"/>
        </node>
      </node>
      <node defType="com.stambia.xml.element" id="_Z_fh-YrqEeqdU-y7qvz1lw" name="bedroom" position="1">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fh-orqEeqdU-y7qvz1lw" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fh-4rqEeqdU-y7qvz1lw" value="-1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_Z_fh_IrqEeqdU-y7qvz1lw" value="mgt:Bedroom"/>
        <node defType="com.stambia.xml.attribute" id="_Z_fh_YrqEeqdU-y7qvz1lw" name="bedroomId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fh_orqEeqdU-y7qvz1lw" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fh_4rqEeqdU-y7qvz1lw" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fiAIrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fiAYrqEeqdU-y7qvz1lw" name="roomNumber" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fiAorqEeqdU-y7qvz1lw" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fiA4rqEeqdU-y7qvz1lw" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fiBIrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fiBYrqEeqdU-y7qvz1lw" name="floor" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fiBorqEeqdU-y7qvz1lw" value="short"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fiB4rqEeqdU-y7qvz1lw" value="xs:short"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fiCIrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fiCYrqEeqdU-y7qvz1lw" name="bath" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fiCorqEeqdU-y7qvz1lw" value="boolean"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fiC4rqEeqdU-y7qvz1lw" value="xs:boolean"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fiDIrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fiDYrqEeqdU-y7qvz1lw" name="shower" position="4">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fiDorqEeqdU-y7qvz1lw" value="boolean"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fiD4rqEeqdU-y7qvz1lw" value="xs:boolean"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fiEIrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fiEYrqEeqdU-y7qvz1lw" name="bar" position="5">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fiEorqEeqdU-y7qvz1lw" value="boolean"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fiE4rqEeqdU-y7qvz1lw" value="xs:boolean"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fiFIrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fiFYrqEeqdU-y7qvz1lw" name="bedCount" position="6">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fiForqEeqdU-y7qvz1lw" value="short"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_fiF4rqEeqdU-y7qvz1lw" value="xs:short"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_fiGIrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_fiGYrqEeqdU-y7qvz1lw" name="phoneNumber" position="7">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_fiGorqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gH8IrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gH8YrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_gH8orqEeqdU-y7qvz1lw" name="bedroomType" position="8">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gH84rqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gH9IrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gH9YrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_Z_gH9orqEeqdU-y7qvz1lw" position="12">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_gH94rqEeqdU-y7qvz1lw" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_gH-IrqEeqdU-y7qvz1lw" value="1"/>
          <node defType="com.stambia.xml.element" id="_Z_gH-YrqEeqdU-y7qvz1lw" name="priceRange" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_gH-orqEeqdU-y7qvz1lw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_gH-4rqEeqdU-y7qvz1lw" value="-1"/>
            <node defType="com.stambia.xml.attribute" id="_Z_gH_IrqEeqdU-y7qvz1lw" name="startDate" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gH_YrqEeqdU-y7qvz1lw" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gH_orqEeqdU-y7qvz1lw" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gH_4rqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gIAIrqEeqdU-y7qvz1lw" name="endDate" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gIAYrqEeqdU-y7qvz1lw" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gIAorqEeqdU-y7qvz1lw" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gIA4rqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gIBIrqEeqdU-y7qvz1lw" name="price" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gIBYrqEeqdU-y7qvz1lw" value="decimal"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gIBorqEeqdU-y7qvz1lw" value="xs:decimal"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gIB4rqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.sequence" id="_Z_gICIrqEeqdU-y7qvz1lw" position="6">
              <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_gICYrqEeqdU-y7qvz1lw" value="1"/>
              <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_gICorqEeqdU-y7qvz1lw" value="1"/>
              <node defType="com.stambia.xml.element" id="_Z_gIC4rqEeqdU-y7qvz1lw" name="occupation" position="0">
                <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_gIDIrqEeqdU-y7qvz1lw" value="0"/>
                <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_gIDYrqEeqdU-y7qvz1lw" value="-1"/>
                <attribute defType="com.stambia.xml.element.originalType" id="_Z_gIDorqEeqdU-y7qvz1lw" value="com:Occupation"/>
                <node defType="com.stambia.xml.attribute" id="_Z_gID4rqEeqdU-y7qvz1lw" name="customerId" position="0">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gIEIrqEeqdU-y7qvz1lw" value="integer"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gIEYrqEeqdU-y7qvz1lw" value="xs:integer"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gIEorqEeqdU-y7qvz1lw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Z_gIE4rqEeqdU-y7qvz1lw" name="occupationDate" position="1">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gIFIrqEeqdU-y7qvz1lw" value="dateTime"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gIFYrqEeqdU-y7qvz1lw" value="xs:dateTime"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gIForqEeqdU-y7qvz1lw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Z_gIF4rqEeqdU-y7qvz1lw" name="personCount" position="2">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gIGIrqEeqdU-y7qvz1lw" value="short"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gIGYrqEeqdU-y7qvz1lw" value="xs:short"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gIGorqEeqdU-y7qvz1lw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Z_gIG4rqEeqdU-y7qvz1lw" name="booked" position="3">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Z_gIHIrqEeqdU-y7qvz1lw" value="boolean"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gIHYrqEeqdU-y7qvz1lw" value="xs:boolean"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Z_gIHorqEeqdU-y7qvz1lw" value="optional"/>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>