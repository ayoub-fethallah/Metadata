<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.wsdl.wsdl" id="_Z_e6NIrqEeqdU-y7qvz1lw" name="geocoder" md:ref="platform:/plugin/com.indy.environment/technology/web/wsdl.tech#UUID_TECH_WSDL1?fileId=UUID_TECH_WSDL1$type=tech$name=wsdl?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.wsdl.wsdl.xsdReverseVersion" id="_Z_fg4IrqEeqdU-y7qvz1lw" value="1"/>
  <attribute defType="com.stambia.wsdl.wsdl.url" id="_Z_fg4YrqEeqdU-y7qvz1lw" value="http://geocoder.stambia.org:62220/geocoder?wsdl"/>
  <attribute defType="com.stambia.wsdl.wsdl.prefixForElement" id="_Z_fg4orqEeqdU-y7qvz1lw" value="unqualified"/>
  <attribute defType="com.stambia.wsdl.wsdl.prefixForAttribute" id="_Z_fg44rqEeqdU-y7qvz1lw" value="unqualified"/>
  <attribute defType="com.stambia.wsdl.wsdl.targetNamespace" id="_Z_fg5IrqEeqdU-y7qvz1lw" value="http://ws.tutorial.demo.indy.com/"/>
  <node defType="com.stambia.xml.namespace" id="_Z_fg5YrqEeqdU-y7qvz1lw" name="http://schemas.xmlsoap.org/wsdl/">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fg5orqEeqdU-y7qvz1lw" value="ns"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_fg54rqEeqdU-y7qvz1lw" name="http://www.w3.org/ns/ws-policy">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fg6IrqEeqdU-y7qvz1lw" value="wsp"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_fg6YrqEeqdU-y7qvz1lw" name="http://ws.tutorial.demo.indy.com/">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fg6orqEeqdU-y7qvz1lw" value="tns"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_fg64rqEeqdU-y7qvz1lw" name="http://schemas.xmlsoap.org/ws/2004/09/policy">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fg7IrqEeqdU-y7qvz1lw" value="wsp1_2"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_fg7YrqEeqdU-y7qvz1lw" name="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-wssecurity-utility-1.0.xsd">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fg7orqEeqdU-y7qvz1lw" value="wsu"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_fg74rqEeqdU-y7qvz1lw" name="http://www.w3.org/2001/XMLSchema">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fg8IrqEeqdU-y7qvz1lw" value="xsd"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_fg8YrqEeqdU-y7qvz1lw" name="http://schemas.xmlsoap.org/wsdl/soap/">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fg8orqEeqdU-y7qvz1lw" value="soap"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_fg84rqEeqdU-y7qvz1lw" name="http://www.w3.org/2007/05/addressing/metadata">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_fg9IrqEeqdU-y7qvz1lw" value="wsam"/>
  </node>
  <node defType="com.stambia.wsdl.service" id="_Z_fg9YrqEeqdU-y7qvz1lw" name="GeoCode_Service">
    <node defType="com.stambia.wsdl.port" id="_Z_fg9orqEeqdU-y7qvz1lw" name="GeoCode_Port">
      <attribute defType="com.stambia.wsdl.port.address" id="_Z_fg94rqEeqdU-y7qvz1lw" value="http://geocoder.stambia.org:62220/geocoder"/>
      <attribute defType="com.stambia.wsdl.port.protocol" id="_Z_fg-IrqEeqdU-y7qvz1lw" value="SOAP"/>
      <attribute defType="com.stambia.wsdl.port.transportURI" id="_Z_fg-YrqEeqdU-y7qvz1lw" value="http://schemas.xmlsoap.org/soap/http"/>
      <attribute defType="com.stambia.wsdl.port.style" id="_Z_fg-orqEeqdU-y7qvz1lw" value="document"/>
      <node defType="com.stambia.wsdl.operation" id="_Z_fg-4rqEeqdU-y7qvz1lw" name="geocode_address">
        <attribute defType="com.stambia.wsdl.operation.style" id="_Z_fg_IrqEeqdU-y7qvz1lw"/>
        <attribute defType="com.stambia.wsdl.operation.actionURI" id="_Z_fg_YrqEeqdU-y7qvz1lw" value=""/>
        <node defType="com.stambia.wsdl.input" id="_Z_fg_orqEeqdU-y7qvz1lw">
          <node defType="com.stambia.wsdl.part" id="_Z_fg_4rqEeqdU-y7qvz1lw" name="parameters">
            <attribute defType="com.stambia.wsdl.part.bindingType" id="_Z_fhAIrqEeqdU-y7qvz1lw" value="soap:body"/>
            <attribute defType="com.stambia.wsdl.part.namespaceURI" id="_Z_fhAYrqEeqdU-y7qvz1lw"/>
            <attribute defType="com.stambia.wsdl.part.use" id="_Z_fhAorqEeqdU-y7qvz1lw" value="literal"/>
            <node defType="com.stambia.xml.element" id="_Z_fhA4rqEeqdU-y7qvz1lw" name="geocode_address" position="0">
              <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhBIrqEeqdU-y7qvz1lw" value="tns:geocode_address"/>
              <node defType="com.stambia.xml.sequence" id="_Z_fhBYrqEeqdU-y7qvz1lw" position="3">
                <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_fhBorqEeqdU-y7qvz1lw" value="1"/>
                <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_fhB4rqEeqdU-y7qvz1lw" value="1"/>
                <node defType="com.stambia.xml.element" id="_Z_fhCIrqEeqdU-y7qvz1lw" name="address" position="0">
                  <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhCYrqEeqdU-y7qvz1lw" value="0"/>
                  <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhCorqEeqdU-y7qvz1lw" value="1"/>
                  <attribute defType="com.stambia.xml.element.type" id="_Z_fhC4rqEeqdU-y7qvz1lw" value="string"/>
                  <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhDIrqEeqdU-y7qvz1lw" value="xsd:string"/>
                </node>
              </node>
            </node>
          </node>
        </node>
        <node defType="com.stambia.wsdl.output" id="_Z_fhDYrqEeqdU-y7qvz1lw">
          <node defType="com.stambia.wsdl.part" id="_Z_fhDorqEeqdU-y7qvz1lw" name="parameters">
            <attribute defType="com.stambia.wsdl.part.bindingType" id="_Z_fhD4rqEeqdU-y7qvz1lw" value="soap:body"/>
            <attribute defType="com.stambia.wsdl.part.namespaceURI" id="_Z_fhEIrqEeqdU-y7qvz1lw"/>
            <attribute defType="com.stambia.wsdl.part.use" id="_Z_fhEYrqEeqdU-y7qvz1lw" value="literal"/>
            <node defType="com.stambia.xml.element" id="_Z_fhEorqEeqdU-y7qvz1lw" name="geocode_addressResponse" position="0">
              <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhE4rqEeqdU-y7qvz1lw" value="tns:geocode_addressResponse"/>
              <node defType="com.stambia.xml.sequence" id="_Z_fhFIrqEeqdU-y7qvz1lw" position="3">
                <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_fhFYrqEeqdU-y7qvz1lw" value="1"/>
                <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_fhForqEeqdU-y7qvz1lw" value="1"/>
                <node defType="com.stambia.xml.element" id="_Z_fhF4rqEeqdU-y7qvz1lw" name="return" position="0">
                  <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhGIrqEeqdU-y7qvz1lw" value="0"/>
                  <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhGYrqEeqdU-y7qvz1lw" value="1"/>
                  <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhGorqEeqdU-y7qvz1lw" value="tns:localisation"/>
                  <node defType="com.stambia.xml.sequence" id="_Z_fhG4rqEeqdU-y7qvz1lw" position="3">
                    <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_fhHIrqEeqdU-y7qvz1lw" value="1"/>
                    <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_fhHYrqEeqdU-y7qvz1lw" value="1"/>
                    <node defType="com.stambia.xml.element" id="_Z_fhHorqEeqdU-y7qvz1lw" name="city" position="0">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhH4rqEeqdU-y7qvz1lw" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhIIrqEeqdU-y7qvz1lw" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_Z_fhIYrqEeqdU-y7qvz1lw" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhIorqEeqdU-y7qvz1lw" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_Z_fhI4rqEeqdU-y7qvz1lw" name="latitude" position="1">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhJIrqEeqdU-y7qvz1lw" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhJYrqEeqdU-y7qvz1lw" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_Z_fhJorqEeqdU-y7qvz1lw" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhJ4rqEeqdU-y7qvz1lw" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_Z_fhKIrqEeqdU-y7qvz1lw" name="longitude" position="2">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhKYrqEeqdU-y7qvz1lw" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhKorqEeqdU-y7qvz1lw" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_Z_fhK4rqEeqdU-y7qvz1lw" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhLIrqEeqdU-y7qvz1lw" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_Z_fhLYrqEeqdU-y7qvz1lw" name="number" position="3">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhLorqEeqdU-y7qvz1lw" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhL4rqEeqdU-y7qvz1lw" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_Z_fhMIrqEeqdU-y7qvz1lw" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhMYrqEeqdU-y7qvz1lw" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_Z_fhMorqEeqdU-y7qvz1lw" name="state" position="4">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhM4rqEeqdU-y7qvz1lw" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhNIrqEeqdU-y7qvz1lw" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_Z_fhNYrqEeqdU-y7qvz1lw" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhNorqEeqdU-y7qvz1lw" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_Z_fhN4rqEeqdU-y7qvz1lw" name="street" position="5">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhOIrqEeqdU-y7qvz1lw" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhOYrqEeqdU-y7qvz1lw" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_Z_fhOorqEeqdU-y7qvz1lw" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhO4rqEeqdU-y7qvz1lw" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_Z_fhPIrqEeqdU-y7qvz1lw" name="zip" position="6">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhPYrqEeqdU-y7qvz1lw" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhPorqEeqdU-y7qvz1lw" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_Z_fhP4rqEeqdU-y7qvz1lw" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhQIrqEeqdU-y7qvz1lw" value="xsd:string"/>
                    </node>
                  </node>
                </node>
              </node>
            </node>
          </node>
        </node>
        <node defType="com.stambia.wsdl.fault" id="_Z_fhQYrqEeqdU-y7qvz1lw" name="Exception">
          <node defType="com.stambia.wsdl.part" id="_Z_fhQorqEeqdU-y7qvz1lw" name="fault">
            <node defType="com.stambia.xml.element" id="_Z_fhQ4rqEeqdU-y7qvz1lw" name="Exception" position="0">
              <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhRIrqEeqdU-y7qvz1lw" value="tns:Exception"/>
              <node defType="com.stambia.xml.sequence" id="_Z_fhRYrqEeqdU-y7qvz1lw" position="3">
                <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_fhRorqEeqdU-y7qvz1lw" value="1"/>
                <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_fhR4rqEeqdU-y7qvz1lw" value="1"/>
                <node defType="com.stambia.xml.element" id="_Z_fhSIrqEeqdU-y7qvz1lw" name="message" position="0">
                  <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_fhSYrqEeqdU-y7qvz1lw" value="0"/>
                  <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_fhSorqEeqdU-y7qvz1lw" value="1"/>
                  <attribute defType="com.stambia.xml.element.type" id="_Z_fhS4rqEeqdU-y7qvz1lw" value="string"/>
                  <attribute defType="com.stambia.xml.element.originalType" id="_Z_fhTIrqEeqdU-y7qvz1lw" value="xsd:string"/>
                </node>
              </node>
            </node>
          </node>
        </node>
        <node defType="com.stambia.wsdl.fault" id="_Z_fhTYrqEeqdU-y7qvz1lw" name="StandardFault">
          <node defType="com.stambia.wsdl.part" id="_Z_fhTorqEeqdU-y7qvz1lw" name="fault">
            <node defType="com.stambia.xml.element" id="_Z_fhT4rqEeqdU-y7qvz1lw" name="faultcode">
              <attribute defType="com.stambia.xml.element.type" id="_Z_fhUIrqEeqdU-y7qvz1lw" value="string"/>
            </node>
            <node defType="com.stambia.xml.element" id="_Z_fhUYrqEeqdU-y7qvz1lw" name="faultstring">
              <attribute defType="com.stambia.xml.element.type" id="_Z_fhUorqEeqdU-y7qvz1lw" value="string"/>
            </node>
            <node defType="com.stambia.xml.element" id="_Z_fhU4rqEeqdU-y7qvz1lw" name="faultactor">
              <attribute defType="com.stambia.xml.element.type" id="_Z_fhVIrqEeqdU-y7qvz1lw" value="string"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>