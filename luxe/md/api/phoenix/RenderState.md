
[![Logo](../../images/logo.png)](../../api/index.html)

<hr/>
<a href="#" id="search_bar" onclick="return;"><div> search API <em>(or start typing anywhere)</em> </div></a>
<hr/>

<script src="../../js/omnibar.js"> </script>
<link rel="stylesheet" type="text/css" href="../../css/omnibar.css" media="all">

<div id="omnibar"> <a href="#" onclick="return" id="omnibar_close"></a> <input id="omnibar_text" type="text" placeholder="search types..."></input></div>
<script  id="typelist" data-relpath="../../" data-types="Luxe,luxe.Audio,luxe.AudioEvent,luxe.AudioHandle,luxe.AudioInstance,luxe.AudioSource,luxe.AudioState,luxe.BitmapFontInfo,luxe.BytesInfo,luxe.Camera,luxe.Circle,luxe.Color,luxe.ColorHSL,luxe.ColorHSV,luxe.Component,luxe.Cursor,luxe.Debug,luxe.DebugError,luxe.Draw,luxe.EmitHandler,luxe.Emitter,luxe.Engine,luxe.Entity,luxe.Ev,luxe.Events,luxe.Game,luxe.GameConfig,luxe.GamepadEvent,luxe.GamepadEventType,luxe.HandlerList,luxe.ID,luxe.IO,luxe.Input,luxe.InputEvent,luxe.InputEventType,luxe.InteractState,luxe.ItemInfo,luxe.JSONInfo,luxe.Key,luxe.KeyEvent,luxe.Log,luxe.Matrix,luxe.Mesh,luxe.ModState,luxe.MouseButton,luxe.MouseEvent,luxe.NineSlice,luxe.Objects,luxe.Parcel,luxe.ParcelChange,luxe.ParcelEvent,luxe.ParcelList,luxe.ParcelProgress,luxe.ParcelState,luxe.Particle,luxe.ParticleEmitter,luxe.ParticleSystem,luxe.Physics,luxe.PhysicsEngine,luxe.PhysicsEvent,luxe.ProjectionType,luxe.Quaternion,luxe.Rectangle,luxe.ResourceEvent,luxe.ResourceState,luxe.ResourceStats,luxe.ResourceType,luxe.Resources,luxe.Scan,luxe.Scene,luxe.Screen,luxe.ShaderInfo,luxe.SizeMode,luxe.SoundInfo,luxe.Sprite,luxe.State,luxe.States,luxe.Tag,luxe.Text,luxe.TextAlign,luxe.TextEvent,luxe.TextEventType,luxe.TextInfo,luxe.TextureInfo,luxe.Timer,luxe.TouchEvent,luxe.Transform,luxe.UserConfig,luxe.Vec,luxe.Vector,luxe.Visual,luxe.WindowEvent,luxe.WindowEventData,luxe.WindowEventType,luxe._Emitter.EmitNode,luxe._Ev.Ev_Impl_,luxe._Events.EventConnection,luxe._Events.EventObject,luxe._Input.MouseButton_Impl_,luxe._Log.LogError,luxe._NineSlice.Slice,luxe._Parcel.ParcelEvent_Impl_,luxe._Parcel.ParcelState_Impl_,luxe._Particles.ParticleEmitterInitData,luxe._Physics.PhysicsEvent_Impl_,luxe._Resources.ResourceEvent_Impl_,luxe._Resources.ResourceState_Impl_,luxe._Resources.ResourceType_Impl_,luxe.collision.Collision,luxe.collision.Results,luxe.collision.ResultsIterator,luxe.collision.ShapeDrawer,luxe.collision.ShapeDrawerLuxe,luxe.collision._Collision.Constructible,luxe.collision.data.RayCollision,luxe.collision.data.RayCollisionHelper,luxe.collision.data.RayIntersection,luxe.collision.data.ShapeCollision,luxe.collision.sat.SAT2D,luxe.collision.shapes.Circle,luxe.collision.shapes.InfiniteState,luxe.collision.shapes.Polygon,luxe.collision.shapes.Ray,luxe.collision.shapes.Shape,luxe.components.Components,luxe.components.cameras.FlyCamera,luxe.components.physics.nape.BoxCollider,luxe.components.physics.nape.BoxColliderOptions,luxe.components.physics.nape.CircleCollider,luxe.components.physics.nape.CircleColliderOptions,luxe.components.physics.nape.NapeBody,luxe.components.physics.nape.NapeBodyOptions,luxe.components.physics.nape.PolygonCollider,luxe.components.physics.nape.PolygonColliderOptions,luxe.components.render.MeshComponent,luxe.components.sprite.SpriteAnimation,luxe.components.sprite.SpriteAnimationData,luxe.components.sprite.SpriteAnimationEventData,luxe.components.sprite.SpriteAnimationFrame,luxe.components.sprite.SpriteAnimationFrameEvent,luxe.components.sprite.SpriteAnimationFrameSource,luxe.components.sprite.SpriteAnimationType,luxe.debug.BatcherDebugView,luxe.debug.DebugInspectorOptions,luxe.debug.DebugView,luxe.debug.Inspector,luxe.debug.ProfilerDebugView,luxe.debug.RenderStats,luxe.debug.SceneDebugView,luxe.debug.StatsDebugView,luxe.debug.TraceDebugView,luxe.debug._ProfilerDebugView.ProfilerBar,luxe.debug._ProfilerDebugView.ProfilerGraph,luxe.debug._ProfilerDebugView.ProfilerValue,luxe.importers.bitmapfont.BitmapFontData,luxe.importers.bitmapfont.BitmapFontParser,luxe.importers.bitmapfont.Character,luxe.importers.obj.Data,luxe.importers.obj.Normal,luxe.importers.obj.Reader,luxe.importers.obj.UV,luxe.importers.obj.Vector,luxe.importers.obj.Vertex,luxe.importers.texturepacker.TexturePackerData,luxe.importers.texturepacker.TexturePackerFrame,luxe.importers.texturepacker.TexturePackerJSON,luxe.importers.texturepacker.TexturePackerJSONType,luxe.importers.texturepacker.TexturePackerMeta,luxe.importers.texturepacker.TexturePackerRect,luxe.importers.texturepacker.TexturePackerSize,luxe.importers.texturepacker.TexturePackerSpriteAnimation,luxe.importers.tiled.TiledImage,luxe.importers.tiled.TiledImageLayer,luxe.importers.tiled.TiledLayer,luxe.importers.tiled.TiledMap,luxe.importers.tiled.TiledMapData,luxe.importers.tiled.TiledMapOptions,luxe.importers.tiled.TiledObject,luxe.importers.tiled.TiledObjectGroup,luxe.importers.tiled.TiledObjectType,luxe.importers.tiled.TiledPolyObject,luxe.importers.tiled.TiledPropertyTile,luxe.importers.tiled.TiledTile,luxe.importers.tiled.TiledTileset,luxe.importers.tiled.TiledUtil,luxe.macros.BuildVersion,luxe.macros.ComponentRules,luxe.macros.EntityRules,luxe.options.AudioResourceOptions,luxe.options.BatcherOptions,luxe.options.BitmapFontOptions,luxe.options.BytesResourceOptions,luxe.options.CameraOptions,luxe.options.CircleGeometryOptions,luxe.options.ColorOptions,luxe.options.ComponentOptions,luxe.options.DrawArcOptions,luxe.options.DrawBoxOptions,luxe.options.DrawCircleOptions,luxe.options.DrawLineOptions,luxe.options.DrawNgonOptions,luxe.options.DrawPlaneOptions,luxe.options.DrawPolygonOptions,luxe.options.DrawRectangleOptions,luxe.options.DrawRingOptions,luxe.options.DrawTextureOptions,luxe.options.EntityOptions,luxe.options.GeometryOptions,luxe.options.JSONResourceOptions,luxe.options.LineGeometryOptions,luxe.options.LoadAudioOptions,luxe.options.LoadFontOptions,luxe.options.LoadShaderOptions,luxe.options.LoadTextureOptions,luxe.options.LuxeCameraOptions,luxe.options.MeshOptions,luxe.options.NineSliceOptions,luxe.options.ParcelOptions,luxe.options.ParcelProgressOptions,luxe.options.ParticleEmitterOptions,luxe.options.ParticleOptions,luxe.options.PlaneGeometryOptions,luxe.options.QuadGeometryOptions,luxe.options.RectangleGeometryOptions,luxe.options.RenderProperties,luxe.options.RenderTextureOptions,luxe.options.ResourceOptions,luxe.options.ShaderOptions,luxe.options.SpriteOptions,luxe.options.StateOptions,luxe.options.StatesOptions,luxe.options.TextOptions,luxe.options.TextResourceOptions,luxe.options.TextureOptions,luxe.options.TileLayerOptions,luxe.options.TileOptions,luxe.options.TilemapOptions,luxe.options.TilemapVisualOptions,luxe.options.TilesetOptions,luxe.options.TransformProperties,luxe.options.VisualOptions,luxe.options._DrawOptions.DrawOptions,luxe.physics.nape.DebugDraw,luxe.physics.nape.PhysicsNape,luxe.physics.nape._DebugDraw.CachedGeometry,luxe.resource.AudioResource,luxe.resource.BytesResource,luxe.resource.JSONResource,luxe.resource.Resource,luxe.resource.TextResource,luxe.structural.BST,luxe.structural.BSTNode,luxe.structural.BSTTraverseMethod,luxe.structural.Bag,luxe.structural.BalancedBST,luxe.structural.BalancedBSTIterator,luxe.structural.BalancedBSTNode,luxe.structural.BalancedBSTTraverseMethod,luxe.structural.Cache,luxe.structural.Heap,luxe.structural.OrderedMap,luxe.structural.OrderedMapIterator,luxe.structural.Pool,luxe.structural.Stack,luxe.structural.StackNode,luxe.structural._Bag.BagNode,luxe.structural._BalancedBST.NodeColor,luxe.tilemaps.Isometric,luxe.tilemaps.IsometricVisual,luxe.tilemaps.Ortho,luxe.tilemaps.OrthoVisual,luxe.tilemaps.Tile,luxe.tilemaps.TileArray,luxe.tilemaps.TileLayer,luxe.tilemaps.TileOffset,luxe.tilemaps.Tilemap,luxe.tilemaps.TilemapOrientation,luxe.tilemaps.TilemapVisual,luxe.tilemaps.TilemapVisualLayerGeometry,luxe.tilemaps.Tileset,luxe.tween.Actuate,luxe.tween.BezierPath,luxe.tween.ComponentPath,luxe.tween.IComponentPath,luxe.tween.LinearPath,luxe.tween.MotionPath,luxe.tween.ObjectHash,luxe.tween.RotationPath,luxe.tween._Actuate.TweenTimer,luxe.tween.actuators.GenericActuator,luxe.tween.actuators.IGenericActuator,luxe.tween.actuators.MethodActuator,luxe.tween.actuators.MotionPathActuator,luxe.tween.actuators.PropertyDetails,luxe.tween.actuators.PropertyPathDetails,luxe.tween.actuators.SimpleActuator,luxe.tween.easing.Back,luxe.tween.easing.BackEaseIn,luxe.tween.easing.BackEaseInOut,luxe.tween.easing.BackEaseOut,luxe.tween.easing.Bounce,luxe.tween.easing.BounceEaseIn,luxe.tween.easing.BounceEaseInOut,luxe.tween.easing.BounceEaseOut,luxe.tween.easing.Cubic,luxe.tween.easing.CubicEaseIn,luxe.tween.easing.CubicEaseInOut,luxe.tween.easing.CubicEaseOut,luxe.tween.easing.Elastic,luxe.tween.easing.ElasticEaseIn,luxe.tween.easing.ElasticEaseInOut,luxe.tween.easing.ElasticEaseOut,luxe.tween.easing.Expo,luxe.tween.easing.ExpoEaseIn,luxe.tween.easing.ExpoEaseInOut,luxe.tween.easing.ExpoEaseOut,luxe.tween.easing.IEasing,luxe.tween.easing.Linear,luxe.tween.easing.LinearEaseNone,luxe.tween.easing.Quad,luxe.tween.easing.QuadEaseIn,luxe.tween.easing.QuadEaseInOut,luxe.tween.easing.QuadEaseOut,luxe.tween.easing.Quart,luxe.tween.easing.QuartEaseIn,luxe.tween.easing.QuartEaseInOut,luxe.tween.easing.QuartEaseOut,luxe.tween.easing.Quint,luxe.tween.easing.QuintEaseIn,luxe.tween.easing.QuintEaseInOut,luxe.tween.easing.QuintEaseOut,luxe.tween.easing.Sine,luxe.tween.easing.SineEaseIn,luxe.tween.easing.SineEaseInOut,luxe.tween.easing.SineEaseOut,luxe.types.user.Game,luxe.utils.GeometryUtils,luxe.utils.Maths,luxe.utils.Random,luxe.utils.Utils,luxe.utils.unifill.CodePoint,luxe.utils.unifill.CodePointIter,luxe.utils.unifill.Exception,luxe.utils.unifill.InternalEncoding,luxe.utils.unifill.InternalEncodingBackwardIter,luxe.utils.unifill.InternalEncodingIter,luxe.utils.unifill.Unicode,luxe.utils.unifill.Unifill,luxe.utils.unifill.Utf16,luxe.utils.unifill.Utf32,luxe.utils.unifill.Utf8,luxe.utils.unifill._CodePoint.CodePoint_Impl_,luxe.utils.unifill._InternalEncoding.UtfX,luxe.utils.unifill._Utf16.StringU16,luxe.utils.unifill._Utf16.StringU16Buffer,luxe.utils.unifill._Utf16.StringU16Buffer_Impl_,luxe.utils.unifill._Utf16.StringU16_Impl_,luxe.utils.unifill._Utf16.Utf16Impl,luxe.utils.unifill._Utf16.Utf16_Impl_,luxe.utils.unifill._Utf32.Utf32_Impl_,luxe.utils.unifill._Utf8.StringU8,luxe.utils.unifill._Utf8.StringU8_Impl_,luxe.utils.unifill._Utf8.Utf8Impl,luxe.utils.unifill._Utf8.Utf8_Impl_,phoenix.BatchState,phoenix.Batcher,phoenix.BatcherEventType,phoenix.BatcherKey,phoenix.BitmapFont,phoenix.BlendEquation,phoenix.BlendMode,phoenix.Camera,phoenix.Circle,phoenix.ClampType,phoenix.Color,phoenix.ColorHSL,phoenix.ColorHSV,phoenix.ComponentOrder,phoenix.DualQuaternion,phoenix.FOVType,phoenix.FilterType,phoenix.Matrix,phoenix.MatrixTransform,phoenix.PrimitiveType,phoenix.ProjectionType,phoenix.Quaternion,phoenix.Ray,phoenix.Rectangle,phoenix.RenderPass,phoenix.RenderPath,phoenix.RenderState,phoenix.RenderTexture,phoenix.Renderer,phoenix.RendererStats,phoenix.Shader,phoenix.Spatial,phoenix.TextAlign,phoenix.Texture,phoenix.TextureDataType,phoenix.TextureFormat,phoenix.TextureID,phoenix.TextureSubmitTarget,phoenix.TextureType,phoenix.Transform,phoenix.Uniforms,phoenix.Vec,phoenix.Vector,phoenix._Batcher.BatcherEventType_Impl_,phoenix._Batcher.BlendEquation_Impl_,phoenix._Batcher.BlendMode_Impl_,phoenix._Batcher.PrimitiveType_Impl_,phoenix._BitmapFont.TextAlign_Impl_,phoenix._Renderer.DefaultShader,phoenix._Renderer.DefaultShaders,phoenix._Shader.Location,phoenix._Shader.Uniform,phoenix._Texture.ClampSlot,phoenix._Texture.ClampSlot_Impl_,phoenix._Texture.ClampType_Impl_,phoenix._Texture.FilterSlot,phoenix._Texture.FilterSlot_Impl_,phoenix._Texture.FilterType_Impl_,phoenix._Texture.TextureSubmitTarget_Impl_,phoenix._Texture.TextureType_Impl_,phoenix._Vector.ComponentOrder_Impl_,phoenix._Vector.Vec_Impl_,phoenix.geometry.ArcGeometry,phoenix.geometry.CircleGeometry,phoenix.geometry.EvTextGeometry,phoenix.geometry.Geometry,phoenix.geometry.GeometryKey,phoenix.geometry.GeometryState,phoenix.geometry.LineGeometry,phoenix.geometry.PackedQuad,phoenix.geometry.PackedQuadOptions,phoenix.geometry.QuadGeometry,phoenix.geometry.QuadPackGeometry,phoenix.geometry.RectangleGeometry,phoenix.geometry.RingGeometry,phoenix.geometry.TextGeometry,phoenix.geometry.TextGeometryOptions,phoenix.geometry.TextureCoord,phoenix.geometry.TextureCoordSet,phoenix.geometry.Vertex,phoenix.geometry._TextGeometry.EvTextGeometry_Impl_,phoenix.utils.Rendering"></script>


<h1>RenderState</h1>
<small>`phoenix.RenderState`

</small>



<hr/>

`class`

<hr/>

&nbsp;



<h3>Members</h3> <hr/><span class="member apipage">
                <a name="bound_texture_2D"><a class="lift" href="#bound_texture_2D">bound\_texture\_2D</a></a><span class="inline-block static">static</span><div class="clear"></div>
                <code class="signature apipage">bound\_texture\_2D : [phoenix.TextureID](../../api/phoenix/TextureID.html)</code><br/></span>
            <span class="small_desc_flat"></span><br/><span class="member apipage">
                <a name="bound_texture_cube"><a class="lift" href="#bound_texture_cube">bound\_texture\_cube</a></a><span class="inline-block static">static</span><div class="clear"></div>
                <code class="signature apipage">bound\_texture\_cube : [phoenix.TextureID](../../api/phoenix/TextureID.html)</code><br/></span>
            <span class="small_desc_flat"></span><br/>


<h3>Methods</h3> <hr/><span class="method apipage">
            <a name="activeTexture"><a class="lift" href="#activeTexture">activeTexture</a></a><div class="clear"></div>
            <code class="signature apipage">activeTexture(val:[Int](http://api.haxe.org/Int.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="bindFramebuffer"><a class="lift" href="#bindFramebuffer">bindFramebuffer</a></a><div class="clear"></div>
            <code class="signature apipage">bindFramebuffer(buffer:[snow.modules.opengl.GLFramebuffer](https://snowkit.github.io/snow/api/snow/modules/opengl/GLFramebuffer.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="bindRenderbuffer"><a class="lift" href="#bindRenderbuffer">bindRenderbuffer</a></a><div class="clear"></div>
            <code class="signature apipage">bindRenderbuffer(buffer:[snow.modules.opengl.GLRenderbuffer](https://snowkit.github.io/snow/api/snow/modules/opengl/GLRenderbuffer.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="bindTexture"><a class="lift" href="#bindTexture">bindTexture</a></a><span class="inline-block static">inline</span><div class="clear"></div>
            <code class="signature apipage">bindTexture(type:[phoenix.TextureType](../../api/phoenix/TextureType.html)<span></span>, tex:[phoenix.TextureID](../../api/phoenix/TextureID.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="bindTexture2D"><a class="lift" href="#bindTexture2D">bindTexture2D</a></a><div class="clear"></div>
            <code class="signature apipage">bindTexture2D(tex:[phoenix.TextureID](../../api/phoenix/TextureID.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="bindTextureCube"><a class="lift" href="#bindTextureCube">bindTextureCube</a></a><div class="clear"></div>
            <code class="signature apipage">bindTextureCube(tex:[phoenix.TextureID](../../api/phoenix/TextureID.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="depthMask"><a class="lift" href="#depthMask">depthMask</a></a><div class="clear"></div>
            <code class="signature apipage">depthMask(\_enable:[Bool](http://api.haxe.org/Bool.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="depth_function"><a class="lift" href="#depth_function">depth\_function</a></a><div class="clear"></div>
            <code class="signature apipage">depth\_function(what:[Int](http://api.haxe.org/Int.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="disable"><a class="lift" href="#disable">disable</a></a><div class="clear"></div>
            <code class="signature apipage">disable(what:[Int](http://api.haxe.org/Int.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="enable"><a class="lift" href="#enable">enable</a></a><div class="clear"></div>
            <code class="signature apipage">enable(what:[Int](http://api.haxe.org/Int.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="lineWidth"><a class="lift" href="#lineWidth">lineWidth</a></a><div class="clear"></div>
            <code class="signature apipage">lineWidth(\_width:[Float](http://api.haxe.org/Float.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="new"><a class="lift" href="#new">new</a></a><div class="clear"></div>
            <code class="signature apipage">new(\_renderer:[phoenix.Renderer](../../api/phoenix/Renderer.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="useProgram"><a class="lift" href="#useProgram">useProgram</a></a><div class="clear"></div>
            <code class="signature apipage">useProgram(program:[snow.modules.opengl.GLProgram](https://snowkit.github.io/snow/api/snow/modules/opengl/GLProgram.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="viewport"><a class="lift" href="#viewport">viewport</a></a><div class="clear"></div>
            <code class="signature apipage">viewport(x:[Float](http://api.haxe.org/Float.html)<span></span>, y:[Float](http://api.haxe.org/Float.html)<span></span>, w:[Float](http://api.haxe.org/Float.html)<span></span>, h:[Float](http://api.haxe.org/Float.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>



<hr/>

&nbsp;
&nbsp;
&nbsp;
&nbsp;