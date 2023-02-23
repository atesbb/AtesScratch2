<template>
  <NucGridPage v-bind:gap="{'row':0,'col':0}" v-bind:designMode="false" overflow="auto" v-bind:rows="[1]"
    v-bind:columns="[1]"
    v-bind:schema="{'r0-c0':{'row':0,'col':0,'rowSpan':1,'colSpan':1,'showIn':['xs','sm','md','lg']}}"
    v-bind:minNsLimit="525"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingBottom':'0px','paddingLeft':'0px','paddingRight':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left" v-bind:row="0"
      v-bind:col="0" v-bind:rowSpan="1" v-bind:colSpan="1" v-bind:marginLeft="0" v-bind:marginRight="0"
      v-bind:marginTop="0" v-bind:marginBottom="0" id="1ffd1b5d-e4a5-4ae9-ae51-11cd4be740b5"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <NucGroupElement v-bind:isLock="false" bgColor="" ncBgType="bgColor" ncTooltipText="" position="absolute"
        top="31.76279069767442%" left="37.58283132530121%" id="050b3df3-db8a-46f9-b6a8-54e80b5dd63e"
        v-bind:style="{'color':'#FFFFFF','width':'379.05','height':'216.6','tabIndex':'-0.722','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'center','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'0.9025','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderColor':'#767676','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'0.722px','textDecoration':'none','borderLeftWidth':'0.722px','borderRightWidth':'0.722px','borderBottomWidth':'0.722px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}">
        <WBlockquoteLabel text="— Author Name, Publication" theme="theme--light01" ncTypography="body1" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          position="absolute" top="29.54840571346126%" left="27.173420173956057%" v-bind:snapX="false"
          v-bind:snapY="false" id="4f4f61bf-8707-466a-8117-8475e3e312cb"
          v-bind:style="{'color':'gray','width':'106.856','height':'12.274','fontSize':'8.664px','fontStyle':'normal','marginTop':'0px','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.0108','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':4}"/>
        <WDefaultCheckbox size="md" label="I accept the terms and use" v-bind:plain="false" theme="theme--light01"
          v-bind:value="true" v-bind:inline="false" fontSize="14px" v-bind:autofocus="false" v-bind:isEnabled="true"
          textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
          v-bind:indeterminate="false" labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="true"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
          ncFocusFontColor="black" ncHoverFontColor="black" ncDisableFontColor="black" ncFocusBorderColor="black"
          ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
          ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent" position="absolute"
          top="68.28163324195643%" left="63.29725050496723%" id="fb996015-e099-41f6-a16c-593791d23103"
          v-bind:style="{'color':'','width':'136.458','height':'47.652','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':5}"/>
      </NucGroupElement>
      <WLargeCheckbox size="lg" label="Large" v-bind:plain="false" theme="theme--light01" v-bind:value="true"
        v-bind:inline="false" fontSize="14px" v-bind:autofocus="false" v-bind:isEnabled="true" textAlign="left"
        fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom" v-bind:indeterminate="false"
        labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="true"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
        ncFocusFontColor="black" ncHoverFontColor="black" ncDisableFontColor="black" ncFocusBorderColor="black"
        ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
        ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent" position="absolute"
        top="13.855377906976743%" left="28.169710090361445%" v-bind:snapX="false" v-bind:snapY="false"
        id="92bef258-2010-4a51-ab78-8d46e813eb01"
        v-bind:style="{'color':'','width':'46.93','height':'21.66','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':3}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>