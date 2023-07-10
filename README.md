
- java.lang.NoSuchMethodError: 'net.fabricmc.loader.game.GameProvider net.fabricmc.loader.FabricLoader.getGameProvider()'
	at me.modmuss50.optifabric.mod.OptifineSetup.getLaunchMinecraftJar(OptifineSetup.java:275)
	at me.modmuss50.optifabric.mod.OptifineSetup.getMinecraftJar(OptifineSetup.java:253)
	at me.modmuss50.optifabric.mod.OptifineSetup.getRuntime(OptifineSetup.java:81)
	at me.modmuss50.optifabric.mod.OptifabricSetup.run(OptifabricSetup.java:41)
	at java.base/java.util.ArrayList.forEach(ArrayList.java:1511)
	at com.chocohead.mm.Plugin.getMixins(Plugin.java:340)
	at org.spongepowered.asm.mixin.transformer.PluginHandle.getMixins(PluginHandle.java:128)
	at org.spongepowered.asm.mixin.transformer.MixinConfig.postInitialise(MixinConfig.java:796)
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.prepareConfigs(MixinProcessor.java:568)
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.select(MixinProcessor.java:462)
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.checkSelect(MixinProcessor.java:438)
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:290)
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:234)
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClassBytes(MixinTransformer.java:202)
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.getPostMixinClassByteArray(KnotClassDelegate.java:422)
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.tryLoadClass(KnotClassDelegate.java:323)
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.loadClass(KnotClassDelegate.java:218)
	at net.fabricmc.loader.impl.launch.knot.KnotClassLoader.loadClass(KnotClassLoader.java:112)
	at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:520)
	at java.base/java.lang.Class.forName0(Native Method)
	at java.base/java.lang.Class.forName(Class.java:467)
	at net.fabricmc.loader.impl.util.DefaultLanguageAdapter.create(DefaultLanguageAdapter.java:50)
	at net.fabricmc.loader.impl.entrypoint.EntrypointStorage$NewEntry.getOrCreate(EntrypointStorage.java:117)
	at net.fabricmc.loader.impl.entrypoint.EntrypointContainerImpl.getEntrypoint(EntrypointContainerImpl.java:53)
	at net.fabricmc.loader.impl.entrypoint.EntrypointUtils.invoke0(EntrypointUtils.java:47)
	at net.fabricmc.loader.impl.entrypoint.EntrypointUtils.invoke(EntrypointUtils.java:35)
	at net.fabricmc.loader.impl.launch.knot.Knot.init(Knot.java:162)
	at net.fabricmc.loader.impl.launch.knot.Knot.launch(Knot.java:68)
	at net.fabricmc.loader.impl.launch.knot.KnotClient.main(KnotClient.java:23)

<!---
haz-q1/haz-q1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
