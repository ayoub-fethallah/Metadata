<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.function.folder" id="_8zLVQENGEe2VR8CUY10zBw" md:ref="resource.md#UUID_MD_UDF?fileId=UUID_MD_UDF$type=md$name=User%20Defined%20Functions?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.function.folder.prefix" id="_QIIXwENHEe2VR8CUY10zBw" value="funct"/>
  <node defType="com.stambia.function.function" id="_QH_N0kNHEe2VR8CUY10zBw" name="concat3">
    <node defType="com.stambia.function.parameter" id="_QH_N00NHEe2VR8CUY10zBw" name="str1" position="1"/>
    <node defType="com.stambia.function.parameter" id="_QH_N1ENHEe2VR8CUY10zBw" name="str2" position="2"/>
    <node defType="com.stambia.function.parameter" id="_QH_N1UNHEe2VR8CUY10zBw" name="str3" position="3"/>
    <node defType="com.stambia.function.implementation" id="_W2yBEUNHEe2VR8CUY10zBw" name="implPGSQL">
      <attribute defType="com.stambia.function.implementation.productCode" id="_g4_s4ENHEe2VR8CUY10zBw">
        <values>POSTGRESSQL</values>
      </attribute>
      <attribute defType="com.stambia.function.implementation.expression" id="_kcwukENHEe2VR8CUY10zBw" value="$str1||$str2||$str3"/>
    </node>
    <node defType="com.stambia.function.implementation" id="_KH4SQUNXEe2VR8CUY10zBw" name="implHSQL">
      <attribute defType="com.stambia.function.implementation.productCode" id="_NiHkgENXEe2VR8CUY10zBw">
        <values>HYPERSONIC_SQL</values>
      </attribute>
      <attribute defType="com.stambia.function.implementation.expression" id="_RGoNEENXEe2VR8CUY10zBw" value="$str1+$str2+$str3"/>
    </node>
  </node>
</md:node>