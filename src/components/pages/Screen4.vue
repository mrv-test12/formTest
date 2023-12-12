<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="77e2d3cc-c355-42d0-9499-070b0829ed5e"
    v-bind:style="{'width':'100%','height':'auto'}">
    <NucGroupElement v-bind:isLock="false" bgColor="" ncBgType="bgColor" ncTooltipText="" position="relative"
      v-bind:snapX="false" v-bind:snapY="false" id="9326f022-9614-40ee-92f1-1e52ae7cf721"
      v-bind:style="{'color':'#FFFFFF','width':'100%','height':'100%','tabIndex':'-1','boxShadow':'','marginTop':'0px','textAlign':'center','lineHeight':'1.25','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderColor':'#767676','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','borderBottomWidth':'1px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}">
      <WDangerButton tag="button" href="" v-bind:pill="false" size="md" text="Danger" type="button" v-bind:block="false"
        color="#FFFFFF" theme="theme--light01" v-bind:rotate="0" v-bind:squared="false" variant="danger"
        v-bind:isEnabled="true" background="#dc3545" linkTarget="_top" ncLinkType="link" borderColor="#dc3545"
        v-bind:resetTrigger="false" animationName="" ncTooltipText="" verticalWidth="60px" formTransition="none"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" toForRouterLink="to" horizontalHeight="37.5347px"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#dc3545"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#dc3545" ncHoverBorderColor="#dc3545"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#dc3545" ncFocusBackgroundColor="#dc3545"
        ncHoverBackgroundColor="#dc3545" ncDisableBackgroundColor="#969696" position="relative" v-bind:snapX="false"
        v-bind:snapY="false" id="7db7950b-3323-4768-bc6f-1fe029545174"
        v-bind:style="{'width':'100%','filter':'none','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'center','fontFamily':'Open Sans','fontWeight':700,'lineHeight':'1.4','marginLeft':'0px','paddingTop':'','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','borderStyle':'solid','marginRight':'0px','paddingLeft':'','wordSpacing':'0px','marginBottom':'0px','mixBlendMode':'normal','paddingRight':'','letterSpacing':'0px','paddingBottom':'','textTransform':'none','backdropFilter':'none','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px','zIndex':4}"/>
      <WButton tag="button" href="" v-bind:pill="false" size="md" text="Button" type="button" v-bind:block="false"
        color="#FFFFFF" theme="theme--light01" v-bind:rotate="0" v-bind:squared="false" variant="primary"
        ncBgType="bgColor" v-bind:isEnabled="true" background="#007bff" linkTarget="_top" ncLinkType="link"
        borderColor="#007bff" v-bind:resetTrigger="false" animationName="" ncTooltipText="" verticalWidth="60px"
        formTransition="none"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" toForRouterLink="to"
        horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        nucalScaleHeight="" ncClickBorderColor="#007BFF" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007BFF"
        ncHoverBorderColor="#007BFF" ncDisableBorderColor="transparent" ncClickBackgroundColor="#007BFF"
        ncFocusBackgroundColor="#007BFF" ncHoverBackgroundColor="#007BFF" ncDisableBackgroundColor="#969696"
        position="relative" v-bind:snapX="false" v-bind:snapY="false" id="ceeb8de5-e9b4-4f38-8763-597c982e6078"
        v-bind:style="{'width':'100%','filter':'none','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','textAlign':'center','fontFamily':'Open Sans','fontWeight':700,'lineHeight':'1.4','marginLeft':'','paddingTop':'','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','borderStyle':'solid','marginRight':'','paddingLeft':'','wordSpacing':'0px','marginBottom':'','mixBlendMode':'normal','paddingRight':'','letterSpacing':'0px','paddingBottom':'','textTransform':'none','backdropFilter':'none','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px','zIndex':5}"/>
    </NucGroupElement>
  </DropZone>
</template>
<script>
import { mapGetters } from 'vuex';
export default {
  name: 'Screen4',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: { ...mapGetters('source', ['getApiMappingWithChain'])},
  methods: {bindSource(chain) { return this.getApiMappingWithChain(chain); }},
  watch: {},
};
</script>

<style lang="scss" scoped>@import 'src/assets/styles/scroll';
 @include custom-scroll();
@media (min-width: 1024.05px){
[id='77e2d3cc-c355-42d0-9499-070b0829ed5e'] {
             display: grid; 
             grid-template-columns: 0 100rem 0;
             grid-template-rows: 0 minmax(62.265625rem, max-content) 0;
          }
[id='9326f022-9614-40ee-92f1-1e52ae7cf721']{
          grid-area: 2/2/3/3;
          }[id='9326f022-9614-40ee-92f1-1e52ae7cf721'] /deep/ > .component-wrapper{
             display: grid; 
             grid-template-columns: 19.21875rem 24.609375rem 13.515625rem 20.46875rem 22.1875rem;
             grid-template-rows: minmax(10.9375rem, max-content) minmax(15.46875rem, max-content) minmax(11.328125rem, max-content) minmax(14.453125rem, max-content) minmax(10.078125rem, max-content);
          }
[id='7db7950b-3323-4768-bc6f-1fe029545174']{
          grid-area: 2/2/3/4;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          }
[id='ceeb8de5-e9b4-4f38-8763-597c982e6078']{
          grid-area: 4/3/5/5;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          }
}
@media (min-width: 768.05px) and (max-width: 1024px){
[id='77e2d3cc-c355-42d0-9499-070b0829ed5e'] {
             display: grid; 
             grid-template-columns: 3.125rem 93.75rem 3.125rem;
             grid-template-rows: 0 minmax(58.3740234375rem, max-content) minmax(3.125rem, max-content);
          }
[id='9326f022-9614-40ee-92f1-1e52ae7cf721']{
          grid-area: 2/2/3/3;
          }[id='9326f022-9614-40ee-92f1-1e52ae7cf721'] /deep/ > .component-wrapper{
             display: grid; 
             grid-template-columns: 3.125rem 4.751536885245902rem 77.9969262295082rem 4.751536885245902rem 3.125rem;
             grid-template-rows: minmax(10.25390625rem, max-content) minmax(14.501953125rem, max-content) minmax(10.6201171875rem, max-content) minmax(13.5498046875rem, max-content) minmax(9.4482421875rem, max-content);
          }
[id='7db7950b-3323-4768-bc6f-1fe029545174']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),2.151639344262295rem);
          }
[id='ceeb8de5-e9b4-4f38-8763-597c982e6078']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),2.151639344262295rem);
          }
}
@media (min-width: 480.05px) and (max-width: 768px){
[id='77e2d3cc-c355-42d0-9499-070b0829ed5e'] {
             display: grid; 
             grid-template-columns: 4.166666667000001rem 91.666666666rem 4.166666667000001rem;
             grid-template-rows: 0 minmax(57.076822916251565rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='9326f022-9614-40ee-92f1-1e52ae7cf721']{
          grid-area: 2/2/3/3;
          }[id='9326f022-9614-40ee-92f1-1e52ae7cf721'] /deep/ > .component-wrapper{
             display: grid; 
             grid-template-columns: 4.166666667rem 4.52527322397131rem 74.28278688405739rem 4.525273223971306rem 4.166666667rem;
             grid-template-rows: minmax(10.02604166659375rem, max-content) minmax(14.179687499896875rem, max-content) minmax(10.384114583257812rem, max-content) minmax(13.248697916570313rem, max-content) minmax(9.238281249932813rem, max-content);
          }
[id='7db7950b-3323-4768-bc6f-1fe029545174']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),2.0491803278360656rem);
          }
[id='ceeb8de5-e9b4-4f38-8763-597c982e6078']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),2.0491803278360656rem);
          }
}
@media (min-width: 375.05px) and (max-width: 480px){
[id='77e2d3cc-c355-42d0-9499-070b0829ed5e'] {
             display: grid; 
             grid-template-columns: 5rem 90rem 5rem;
             grid-template-rows: 0 minmax(56.03906249999999rem, max-content) minmax(5rem, max-content);
          }
[id='9326f022-9614-40ee-92f1-1e52ae7cf721']{
          grid-area: 2/2/3/3;
          }[id='9326f022-9614-40ee-92f1-1e52ae7cf721'] /deep/ > .component-wrapper{
             display: grid; 
             grid-template-columns: 5rem 4.344262295081968rem 71.31147540983605rem 4.344262295081974rem 5rem;
             grid-template-rows: minmax(9.84375rem, max-content) minmax(13.921874999999998rem, max-content) minmax(10.195312499999998rem, max-content) minmax(13.007812499999998rem, max-content) minmax(9.070312499999998rem, max-content);
          }
[id='7db7950b-3323-4768-bc6f-1fe029545174']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),1.967213114754098rem);
          }
[id='ceeb8de5-e9b4-4f38-8763-597c982e6078']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),1.967213114754098rem);
          }
}
@media (min-width: 0px) and (max-width: 375px){
[id='77e2d3cc-c355-42d0-9499-070b0829ed5e'] {
             display: grid; 
             grid-template-columns: 6.4rem 87.2rem 6.4rem;
             grid-template-rows: 0 minmax(54.295625rem, max-content) minmax(6.4rem, max-content);
          }
[id='9326f022-9614-40ee-92f1-1e52ae7cf721']{
          grid-area: 2/2/3/3;
          }[id='9326f022-9614-40ee-92f1-1e52ae7cf721'] /deep/ > .component-wrapper{
             display: grid; 
             grid-template-columns: 6.4rem 4.040163934426228rem 66.31967213114756rem 4.040163934426228rem 6.4rem;
             grid-template-rows: minmax(9.537500000000001rem, max-content) minmax(13.48875rem, max-content) minmax(9.878125rem, max-content) minmax(12.603125000000002rem, max-content) minmax(8.788125000000003rem, max-content);
          }
[id='7db7950b-3323-4768-bc6f-1fe029545174']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),1.8295081967213118rem);
          }
[id='ceeb8de5-e9b4-4f38-8763-597c982e6078']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),1.8295081967213118rem);
          }
}
</style>